# demo-static

Live demo tampilan GoMad — di-deploy sebagai static page ke `demo.gomad.id`.

## Isi
Folder ini berisi mockup UI statis per role/halaman (tanpa backend):
- `customer/` — tampilan sisi pelanggan
- `driver/` — tampilan sisi supir
- `agency/` — tampilan sisi agency
- `login/`, `register/`, `forgot-password/` — halaman autentikasi
- `search/`, `listing/`, `rental/`, `e-ticket/`, `download-app/` — halaman fitur
- `demo/` — halaman index demo
- `index.html` — entry point

## Deploy
Static page (Render / Netlify). Tidak butuh build step.

## Catatan
- Murni statis (HTML + CSS inline), tidak terhubung ke API backend.
- Digunakan untuk demo/presentasi tampilan sebelum rilis.
