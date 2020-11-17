# FreshFruit
![Diagram](https://user-images.githubusercontent.com/62002219/99422865-8ae06f00-2932-11eb-808e-84ce3bf64482.JPG)

Fungsi dari BucketEventListener
Menghandle event bucket saat gagal atau berhasil

Logika Algoritma
       Seller Addnan;

        public MainWindow()
        {
            InitializeComponent();

            Bucket keranjangBuah = new Bucket(2);
            BucketController bucketController = new BucketController(keranjangBuah, this);

            Addnan = new Seller("Addnan", bucketController);

            ListBoxBucket.ItemsSource = keranjangBuah.findAll();
        }
Membuat intance Addnan sebagai user

        private void Button1_Click(object sender, RoutedEventArgs e)
        {
            Fruit anggur = new Fruit("Anggur");
            Addnan.addFruit(anggur);
        }

Untuk mengoprasikan button agar melanjutkan proses ke bucket, ada 4 button tepatnya

pada folder model kurang lebih untuk mendeklarasikan operasi dan proses2 pada bucket dan seller
