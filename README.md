# World Wide Startup Visualization

Proyek ini untuk memenuhi tugas mata kuliah Visualisasi Data, Telkom University.
Website ini menampilkan visualisasi data mengenai Startup Unicorn yang ada di seluruh dunia per bulan July 2023. Data tersebut diambil dari https://www.kaggle.com/datasets/tahzeer/unicorn-startup-companies-july-2023. Data tersebut berisikan mengenai daftar Startup yang ada diseluruh dunia yang memuat beberapa data yakni nilai valuasi perusahaan tersebut, tanggal berdirinya, asal negara, asal kota, kategori industri, dan investor yang mendanai startup tersebut.

## Visualisasi Data

Terdapat 3 visualisasi data yang ditampilkan, yakni:

- ### Top 10 Company Valuation ($ Billions)
  Visualisasi Data yang menampilkan terkait 10 besar perusahaan startup yang memiliki valuasi tertinggi. Terdapat custom filter berdasarkan year, country, dan industry. Data tersebut divisualisasikan dalam bentuk Grafik Batang dengan arah Horizontal agar mudah dipahami oleh berbagai orang tanpa memerlukan pengetahuan statistik atau matematika yang mendalam juga memberikan visualisasi yang jelas dan langsung tentang perbandingan antar grup data.
- ### Total Valuation by Industry/Country
  Visualisasi Data yang menampilkan terkait total dari valuasi perusahaan startup yang dikategorikan berdasarkan Industry atau Country. Terdapat custom filter berdasarkan year, country, dan industry. Data tersebut divisualisasikan dalam bentuk Grafik Batang dengan arah Vertikal agar mudah dipahami oleh berbagai orang tanpa memerlukan pengetahuan statistik atau matematika yang mendalam juga memberikan visualisasi yang jelas dan langsung tentang perbandingan antar grup data.
- ### Growth of Startup By Year Joined
  Visualisasi Data yang menampilkan terkait pertumbuhan banyaknya startup pada setiap tahunnya. Terdapat custom filter berdasarkan year, country, dan industry. Data tersebut divisualisasikan dalam bentuk Grafik Multi Line Chart untuk membandingkan tren atau perubahan seiring waktu di beberapa kategori atau variabel. Setiap garis dapat mewakili satu kategori atau grup, memungkinkan pengguna untuk melihat hubungan dan perubahan secara visual.

## An Overview of Development Process:

- Pemilihan Data
  Dalam melakukan pemilihan data, saya memilih untuk mencari dataset pada Kaggle.com yang merupakan satu situs pencarian dataset dengan komunitas yang besar. Kemudian saya berpikir untuk memvisualisasikan data terkait Startup karena trend pada perusahaan saat ini. Dan akhirnya saya mendapatkan data terkait startup unicorn yang ada di seluruh dunia per Juli 2023.
- Exploratory Analysis
  Proses untuk mengeksplorasi dan mengidentifikasi pola, tren, anomali, dan hubungan dalam data tanpa batasan awal. Mencari apa saja yang dapat diolah dari data yang telah didapatkan. Dan saya menemukan peluang untuk menampilkan data tersebut untuk divisualisasikan yakni peringkat valuasi dengan beberapa filterisasi yang dapat digunakan dari Year, Country dan Industry
- Eksplorasi Teknologi
  Disini saya mencari beberapa teknologi untuk dapat melakukan visualisasi data tersebut. Dan akhirnya saya memutuskan untuk memilih menggunakan ObservableHQ karena dapat memproses data untuk dapat divisualisasikan secara cepat, interaktif, dan kemudahan dalam pengoperasian alat tersebut.
- Implementasi
  Pada implementasinya, saya melakukan import data pada notebook yang disediakan pada ObservableHQ, dan melakukan beberapa Query data untuk melakukan pemilhan dan pengambilan data berdasarkan tujuan yang diinginkan. Setelah data tersebut diambil dan dipilah, selanjutnya data tersebut diimplementasikan pada script agar dapat divisualisasikan pada chart yang diinginkan.
- Deployment
  Diakhir implementasi, saya melakukan deployment dari proyek yang telah dikembangkan pada Github karena mudah dan tidak memerlukan biaya dalam melakukan deployment tersebut.
