| time                | author                                        |
| ------------------- | ----------------------------------------------|
| 2020-10-07 12:29:00 | [Virdio Samuel](https://github.com/diosamuel) |

# Operator

Operator adalah simbol yang digunakan untuk melakukan operasi tertentu pada suatu nilai dan variabel.

Didalam Javascript terdapat banyak jenis operator, seperti

1. [Operator Aritmatika](#Operator-Aritmatika)
2. Operator Komparasi
3. Operator Logika
4. Operator Assignment

---

# Operator Aritmatika

Operator Aritmatika meliputi simbol simbol matematika seperti

| Nama | Simbol |Penjelasan  |
|----------|--------|------------|
|Tambah    |	+	| Penjumlahan|
|Kurang    |	-	| Pengurangan|
|Bagi	   |	/	| Pembagian  |
|Kali	   |	*	| Perkalian	 |
|Pangkat   |	**	| Pemangkatan|
|Modulus   |	%	| Sisa bagi  |

*Contoh*
```javascript
console.log(10**2)//10 pangkat 2
console.log(20/5)//20 bagi 2
````

# Operator Komparasi

Operator Komparasi (Perbandingan) digunakan untuk membandingkan suatu nilai maupun variabel

| Nama   			 		 | Simbol 		  |
|----------------------------|----------------|
| Lebih besar dari	 		 |	>     		  |
| Lebih besar sama dengan	 |	>=     		  |
| Lebih kecil dari	 		 | <	  		  |
| Lebih kecil sama dengan	 | <=	  		  |
| Sama dengan	     		 | == atau ===	  |
| Tidak sama dengan  		 | != atau !==    |

**Tip!**
*Apa perbedaan == dengan ===, dan != dengan !==?*

```=== dan !==``` digunakan untuk membandingkan suatu nilai atau variabel, tetapi melihat **[tipe data](./06-tipe-data.md)** nya terlebih dahulu.
Sedangkan ```== dan !=``` membandingkan suatu nilai atau variabel tanpa melihat **[tipe data](./06-tipe-data.md)** terlebih dahulu

contoh

```javascript
console.log(60=='60')//true
console.log(60==='60')//false, karena berbeda tipe (String dan Number)

console.log(60!='60')//false
console.log(60!=='60')//true, karena berbeda tipe (String dan Number)
```

# Operator Logika

Operator logika ini digunakan untuk melakukan operasi terhadap dua nilai / variabel boolean (true dan false)


| Nama   | Simbol | Penjelasan |
|--------|--------|------------|
| AND    | &&     | true jika kedua hasil boolean dari nilai adalah true
| OR     |&#124;&#124;| true jika salah satu dari kedua hasil boolean dari nilai adalah true |
| Negasi | !      | Membalikkan booelan |

contoh

```javascript
console.log(true&&false)//output : false
console.log(true&&true)//output : true

console.log(true||false)//output : true
console.log(true||true)//output : true

console.log(!true)//output : false
```