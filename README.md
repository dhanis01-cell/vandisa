# vandisa<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cara Membuat Situs Web Sendiri</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            overflow: hidden;
        }
        
        header {
            background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
            color: white;
            padding: 60px 40px;
            text-align: center;
        }
        
        h1 {
            font-size: 3rem;
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }
        
        .subtitle {
            font-size: 1.2rem;
            opacity: 0.9;
            max-width: 600px;
            margin: 0 auto;
        }
        
        .content {
            padding: 40px;
        }
        
        .steps {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin: 40px 0;
        }
        
        .step {
            background: #f8f9fa;
            padding: 30px;
            border-radius: 15px;
            border-left: 4px solid #4facfe;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .step:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
        }
        
        .step h3 {
            color: #4facfe;
            margin-bottom: 15px;
            font-size: 1.5rem;
        }
        
        .step p {
            margin-bottom: 15px;
            color: #666;
        }
        
        .tools {
            background: #e3f2fd;
            padding: 30px;
            border-radius: 15px;
            margin: 40px 0;
        }
        
        .tools h2 {
            text-align: center;
            margin-bottom: 20px;
            color: #0d47a1;
        }
        
        .tool-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        
        .tool {
            background: white;
            padding: 15px 25px;
            border-radius: 25px;
            font-weight: bold;
            color: #1976d2;
            border: 2px solid #1976d2;
            transition: all 0.3s ease;
        }
        
        .tool:hover {
            background: #1976d2;
            color: white;
            transform: scale(1.05);
        }
        
        .conclusion {
            text-align: center;
            padding: 40px;
            background: linear-gradient(135deg, #ff6b6b 0%, #ee5a24 100%);
            color: white;
            margin-top: 40px;
        }
        
        .conclusion h2 {
            margin-bottom: 20px;
            font-size: 2rem;
        }
        
        .conclusion p {
            max-width: 600px;
            margin: 0 auto 20px;
            font-size: 1.1rem;
        }
        
        .btn {
            display: inline-block;
            background: white;
            color: #ff6b6b;
            padding: 12px 30px;
            border-radius: 25px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 20px;
            transition: all 0.3s ease;
        }
        
        .btn:hover {
            transform: scale(1.1);
            box-shadow: 0 10px 20px rgba(0,0,0,0.2);
        }
        
        footer {
            text-align: center;
            padding: 20px;
            background: #333;
            color: white;
        }
        
        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }
            
            .content {
                padding: 20px;
            }
            
            .steps {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Cara Membuat Situs Web Sendiri</h1>
            <p class="subtitle">Panduan lengkap untuk pemula yang ingin membuat website pertama mereka</p>
        </header>
        
        <div class="content">
            <div class="steps">
                <div class="step">
                    <h3>1. Tentukan Tujuan Website</h3>
                    <p>Sebelum mulai coding, tentukan tujuan website Anda. Apakah untuk portofolio, blog, toko online, atau informasi perusahaan?</p>
                    <p>Ini akan membantu menentukan fitur dan desain yang dibutuhkan.</p>
                </div>
                
                <div class="step">
                    <h3>2. Pelajari Dasar Web Development</h3>
                    <p>Pelajari tiga teknologi dasar:</p>
                    <ul>
                        <li><strong>HTML</strong> - Struktur website</li>
                        <li><strong>CSS</strong> - Desain dan tampilan</li>
                        <li><strong>JavaScript</strong> - Interaktivitas</li>
                    </ul>
                </div>
                
                <div class="step">
                    <h3>3. Pilih Platform atau Framework</h3>
                    <p>Untuk pemula, Anda bisa mulai dengan:</p>
                    <ul>
                        <li>Website builder (Wix, WordPress)</li>
                        <li>Coding manual dengan HTML/CSS/JS</li>
                        <li>Framework modern (React, Vue, Angular)</li>
                    </ul>
                </div>
                
                <div class="step">
                    <h3>4. Beli Domain dan Hosting</h3>
                    <p>Domain adalah alamat website Anda (contoh: namakamu.com). Hosting adalah tempat menyimpan file website.</p>
                    <p>Beberapa penyedia populer: Niagahoster, Hostinger, atau layanan gratis seperti GitHub Pages.</p>
                </div>
                
                <div class="step">
                    <h3>5. Desain dan Bangun Website</h3>
                    <p>Buat desain wireframe terlebih dahulu, lalu implementasikan dengan kode atau tools yang Anda pilih.</p>
                    <p>Perhatikan user experience (UX) dan user interface (UI).</p>
                </div>
                
                <div class="step">
                    <h3>6. Uji dan Publikasikan</h3>
                    <p>Uji website di berbagai perangkat dan browser. Pastikan semuanya berfungsi dengan baik sebelum dipublikasikan.</p>
                    <p>Jangan lupa optimasi untuk SEO!</p>
                </div>
            </div>
            
            <div class="tools">
                <h2>Tools yang Berguna untuk Pemula</h2>
                <div class="tool-list">
                    <div class="tool">VS Code</div>
                    <div class="tool">GitHub</div>
                    <div class="tool">Figma</div>
                    <div class="tool">Chrome DevTools</div>
                    <div class="tool">Canva</div>
                    <div class="tool">Google Fonts</div>
                </div>
            </div>
            
            <div class="conclusion">
                <h2>Mulai Sekarang!</h2>
                <p>Jangan takut untuk memulai. Setiap developer hebat pernah menjadi pemula. Konsistensi dan praktik adalah kunci utama.</p>
                <p>Ingat: Website pertama Anda tidak harus sempurna. Yang penting adalah mulai!</p>
                <a href="#" class="btn">Mulai Belajar Sekarang</a>
            </div>
        </div>
        
        <footer>
            <p>&copy; 2024 Panduan Membuat Website. Semua hak dilindungi.</p>
        </footer>
    </div>
</body>
</html>
