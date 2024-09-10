from google.colab import drive
drive.mount('/content/drive')

# Lihat isi direktori root Google Drive
!ls /content/drive/

# Baca file Excel dari Google Drive
import pandas as pd
df = pd.read_excel('/content/drive/MyDrive/data.xlsx')
df
