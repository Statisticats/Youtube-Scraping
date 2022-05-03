# Youtube Data Scraping and Exploration
Dalam repository ini, dilakukan scraping data Youtube dan eksplorasi data hasil scraping menggunakan Python. Scraping data Youtube dilakukan pada 5 channel berita terbesar di Indonesia yaitu KompasTV, CNN Indonesia, tvOneNews, Tribunnews, dan Tribun Timur. Data diambil menggunakan Youtube API pada tanggal 22 April 2022. Tutorial scraping data dengan Youtube API dapat dilihat <a href="https://github.com/Statisticats/Youtube-Scraping/blob/main/Youtube%20Scraping%20-%20News%20Channel.ipynb">disini</a>. Selain itu, dilakukan eksplorasi pada data hasil scraping video channel KompasTV yang di ambil pada tanggal 28 April 2022 yang dapat dilihat <a href="https://github.com/Statisticats/Youtube-Scraping/blob/main/Youtube%20Video%20Data%20Exploration.ipynb">disini</a>.

## Youtube Data Scraping
### Peubah yang digunakan
<ol>
  <li>Nama Channel</li>
  <li>Create Date : Tanggal pembuatan channel</li>
  <li>Subscribers : Banyaknya subscriber channel</li>
  <li>Total Views : Total banyaknya views dari seluruh video yang telah diunggah</li>
  <li>Total Video : Banyaknya video yang telah diunggah</li>
  <li>Playlist ID : Identitas playlist yang berisi seluruh video yang telah diunggah dari suatu channel</li>
</ol>

### Package yang digunakan
<ol>
  <li>googleapiclient.discovery</li>
  <li>pandas</li>
  <li>seaborn</li>
</ol>

### Tahapan
<ol>
  <li>Mendapatkan Youtube API</li>
  <li>Scraping Statistik dari Channel</li>
  <li>Scraping VideoID dari Channel</li>
  <li>Scraping Scraping Video Details berdasarkan VideoID</li>
</ol>

## Youtube Data Exploration
### Peubah yang digunakan
<ol>
  <li>VideoID     : Identitas video yang telah diunggah </li>
  <li>Title       : Judul video</li>
  <li>PublishedAt : Tanggal pengunggahan video</li>
  <li>Tags        : Tag dari video yang dimasukkan oleh pengunggah</li>
  <li>Duration    : Durasi video</li>
  <li>Likes       : Banyak like yang didapatkan dari video</li>
  <li>Views       : Banyak viewers dari video</li>
  <li>CommentCount: Banyak comment dari video</li>
</ol>

### Package yang digunakan
<ol>
  <li>pandas</li>
  <li>seaborn</li>
  <li>isodate</li>
  <li>numpy</li>
  <li>re</li>
  <li>sastrawi</li>
  <li>nltk</li>
  <li>sklearn</li>
  <li>matplotlib</li>
</ol>

### Eksplorasi
<ol>
  <li>Penyesuaian Format Data</li>
  <li>Eksplorasi Peubah Views</li>
  <li>Eksplorasi Peubah Likes</li>
  <li>Eksplorasi Peubah PublishedAt</li>
  <li>Eksplorasi Peubah Title</li>
  <li>Eksplorasi Peubah Duration</li>
</ol>

## Find more
Instagram : <a href="https://www.instagram.com/statisticats.co">statisticats.co</a>

Medium    : <a href="https://medium.com/@statisticats">Statisticats</a>

## Contributors
<ul>
  <li>Aisyah Fadila          : <a href="https://github.com/Aisyahfdl14">@AisyahFdl14</a></li> 
  <li>Nindi Pigitha          : <a href="https://github.com/pigithanindi">@pigithanindi</a></li>
  <li>Tiara Lutfiah Adisti   : <a href="https://github.com/adisti24">@adisti24</a></li>
</ul>
