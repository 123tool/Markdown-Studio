## Markdown Studio — Advanced Table Generator

Markdown Studio adalah aplikasi berbasis web kelas premium produksi (production-ready) yang dirancang untuk mengonversi data tabel interaktif spreadsheet secara instan menjadi format teks Markdown standar. Aplikasi ini juga dilengkapi dengan mesin pencari parser *live preview* real-time berbasis standar **GitHub-Flavored Markdown (GFM)** yang diamankan menggunakan lapisan proteksi sanitasi ketat untuk mencegah serangan Cross-Site Scripting (XSS).

Diproduksi dengan arsitektur bersih (*clean-code architecture*) tanpa membutuhkan framework berat, aplikasi ini sangat optimal, responsif, dan siap di-deploy langsung tanpa konfigurasi tambahan.

---

## Fitur Utama & Keunggulan

* **Dynamic Matrix Table Generator**: Tambah, kurangi, dan ubah dimensi baris dan kolom tabel secara instan menggunakan antarmuka grid yang responsif.
* **Column Alignment Control**: Pengaturan perataan baris data kolom (Kiri, Tengah, Kanan) secara individual melalui satu tombol interaktif dengan sinkronisasi penanda sintaksis Markdown (`:---`, `:---:`, `---:`).
* **Instant Preset Templates**: Mempercepat alur kerja menggunakan template bawaan siap pakai (seperti *Pricing Plan Table* dan *Tech Specifications Table*).
* **Dual Mode Engine Preview Layout**: 
    * *Rendered HTML View*: Hasil render teks Markdown secara visual menggunakan representasi CSS yang identik dengan dokumentasi resmi GitHub Markdown Core.
    * *Raw Editor Sandbox Mode*: Tempat eksperimen penulisan sintaksis teks Markdown kustom secara bebas (mendukung pengujian teks tebal, miring, list, blockquote, kode blok, dll).
* **Advanced XSS Sanitation**: Memanfaatkan **DOMPurify** dikombinasikan dengan parser **Marked.js** untuk menyaring semua potensi kode berbahaya (*malicious script injection*), menjamin keamanan penuh pada lingkungan web produksi.
* **Single-File Serverless Architecture**: Tidak memerlukan kompilasi Node.js, Webpack, atau instalasi `node_modules` yang kompleks. Mudah diintegrasikan ke platform statis seperti GitHub Pages, Cloudflare Pages, Vercel, Netlify, hingga widget kustom seperti Google Blogger.
