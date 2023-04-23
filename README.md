#Pemrograman fungsional
#Mendefinisikan daftar harga
harga = [10, 20, 30, 40]

#Mendefinisikan fungsi untuk menghitung total harga
def total(harga):
  jumlah pengembalian (harga)

#Mencetak hasil dari fungsi total() dengan harga parameter
cetak(total(harga))


#OOP (Pemrograman Berorientasi Objek)
#Mendefinisikan sebuah class Item untuk merepresentasikan sebuah item
Barang kelas:
  def _init_(diri, nama, harga):
    self.nama = nama
    self.harga = harga

#Mendefinisikan sebuah class ShoppingCart untuk merepresentasikan sebuah shopping cart
kelas Keranjang Belanja:
  def _init_(diri sendiri):
    diri.item = []

  def add_item(self, item):
    self.items.append(item)

  def total(diri):
    #Menghitung total harga dari seluruh barang di dalam keranjang belanja
    jumlah pengembalian(item.price untuk item di self.items)

#Membuat sebuah instance dari class ShoppingCart
keranjang = Keranjang Belanja()

#Menambahkan beberapa item ke dalam keranjang belanja
cart.add_item(Barang("Buku", 10))
cart.add_item(Barang("Pulpen", 5))
cart.add_item(Barang("Kertas", 20))

#Mencetak total harga dari seluruh barang di dalam keranjang belanja
cetak(keranjang.total())
