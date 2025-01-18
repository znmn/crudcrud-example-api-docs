# Dokumentasi API Berita CRUDCRUD

Ini adalah dokumentasi untuk API Berita CRUDCRUD. API ini memungkinkan Anda untuk melakukan operasi CRUD dasar (Create, Read, Update, Delete) pada artikel berita. Anda dapat menggunakan API ini untuk mengintegrasikan fitur manajemen berita ke dalam aplikasi Anda, seperti situs web, aplikasi seluler, dan lainnya.

## Daftar Isi

- [Live Documentation](#live-documentation)
- [Fitur](#fitur)
- [Endpoint](#endpoint)
- [Memulai](#memulai)
- [Contoh Penggunaan](#contoh-penggunaan)

## Live Documentation

[Live Documentation - Swagger 2](https://znmn.github.io/crudcrud-example-api-docs) dapat diakses melalui link berikut: https://znmn.github.io/crudcrud-example-api-docs
[Live Documentation - OAS 3](https://znmn.github.io/crudcrud-example-api-docs/V3) dapat diakses melalui link berikut: https://znmn.github.io/crudcrud-example-api-docs/V3

## Fitur

- Membaca artikel berita.
- Membuat artikel berita baru.
- Memperbarui artikel berita yang ada.
- Menghapus artikel berita.

## Endpoint

- `GET /news`: Dapatkan daftar artikel berita.
- `GET /news/{_id}`: Dapatkan detail artikel berita tertentu berdasarkan ID.
- `POST /news`: Buat artikel berita baru.
- `PUT /news/{_id}`: Perbarui artikel berita yang ada.
- `DELETE /news/{_id}`: Hapus artikel berita berdasarkan ID.

## Memulai

1. Ambil Apikey URL melalui https://crudcrud.com/

2. Ubah basePath pada file [crudcrud.json](json/crudcrud.json), dengan menambahkan apiKey yang telah didapat

3. Jalankan file [index.html](index.html) pada browser

4. Gantilah `{_id}` dengan ID data yang ingin Anda akses atau ubah.

## Contoh Penggunaan

### Mendapatkan Daftar Artikel Berita

```http
GET https://crudcrud.com/api/{apiKey}/news
```
