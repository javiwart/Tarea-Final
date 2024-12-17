# Tarea-Final
Proyecto Final JM
import yfinance as yf

# Descargar los datos históricos de Tesla
tesla = yf.Ticker("TSLA")
tesla_data = tesla.history(period="1y")  # Datos de 1 año

# Mostrar los primeros registros
tesla_data.head()
