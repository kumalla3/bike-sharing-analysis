# Bike Sharing Dashboard

Dashboard analisis data peminjaman sepeda menggunakan dataset Bike Sharing (2011-2012).

## Setup Environment

### Menggunakan Anaconda
conda create --name main-ds python=3.9
conda activate main-ds
pip install -r requirements.txt

### Menggunakan Shell/Terminal
mkdir proyek_analisis_data
cd proyek_analisis_data
pipenv install
pipenv shell
pip install -r requirements.txt

## Menjalankan Dashboard

cd submission
streamlit run dashboard/dashboard.py

Dashboard akan terbuka otomatis di browser pada alamat: http://localhost:8501
