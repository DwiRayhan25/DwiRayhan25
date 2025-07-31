<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profil Mahasiswa</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f4f8;
            color: #333;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 800px;
            margin: 40px auto;
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }
        h1 {
            text-align: center;
            color: #0056b3;
        }
        .profile {
            display: flex;
            align-items: center;
            gap: 20px;
            margin-top: 30px;
        }
        .profile img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid #0056b3;
        }
        .profile-info {
            flex: 1;
        }
        .info-item {
            margin-bottom: 10px;
        }
        .info-item strong {
            display: inline-block;
            width: 120px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Profil Mahasiswa</h1>
        <div class="profile">
            <img src="https://via.placeholder.com/150" alt="Foto Mahasiswa">
            <div class="profile-info">
                <div class="info-item"><strong>Nama:</strong> Muhammad Dwi Rayhan Syarif</div>
                <div class="info-item"><strong>NIM:</strong> 123456789</div>
                <div class="info-item"><strong>Jurusan:</strong> Ekonomi Syariah</div>
                <div class="info-item"><strong>Universitas:</strong> Universitas Negeri Contoh</div>
                <div class="info-item"><strong>Email:</strong> rayhan@student.univcontoh.ac.id</div>
            </div>
        </div>
    </div>
</body>
</html>
