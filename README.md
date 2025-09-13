# KapselAndat
Tugas 1

# Panduan Penyelesaian Persamaan Diferensial Biasa

Dokumen ini berisi langkah-langkah untuk menyelesaikan persamaan diferensial biasa (Ordinary Differential Equation - ODE) berbentuk:

$$ \frac{dy}{dx} = f(x, y) $$

## Langkah 1: Klasifikasi Persamaan

Identifikasi jenis persamaan diferensial (misalnya, variabel terpisah, homogen, eksak, atau linear) untuk menentukan metode penyelesaian yang tepat.

## Langkah 2: Penerapan Metode

Misalkan kita ingin menyelesaikan persamaan diferensial sederhana:

$$ \frac{dy}{dx} = 2x $$

### Variabel Terpisah

Pindahkan semua suku $y$ ke satu sisi dan semua suku $x$ ke sisi lain.

$$ dy = \int 2x\ dx $$

### Integrasikan Kedua Sisi

Ambil integral dari kedua sisi persamaan.

$$ \int dy = \int 2x \ dx $$

$$ y = x^2 + C $$

di mana $C$ adalah konstanta integrasi.

## Langkah 3: Menemukan Solusi Khusus (Jika Ada Kondisi Awal)

Jika diberikan kondisi awal, misalnya  $y(1) = 3$ , substitusikan nilai-nilai tersebut untuk menemukan nilai $C$.

$$ 3 = (1)^2 + C $$

$$ 3 = 1 + C $$

$$ C = 2 .$$

Maka, solusi khusus untuk persamaan ini adalah

$$y = x^2 + 2 .$$
