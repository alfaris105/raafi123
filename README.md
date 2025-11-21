<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>APK Builder</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "Poppins", sans-serif;
        }

        body {
            background: #0c0c0c;
            color: white;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .card {
            width: 100%;
            max-width: 550px;
            background: rgba(255, 255, 255, 0.05);
            border: 1px solid rgba(255, 255, 255, 0.15);
            border-radius: 20px;
            padding: 30px;
            text-align: center;
            backdrop-filter: blur(10px);
            animation: fadeIn 0.8s ease-in-out;
        }

        @keyframes fadeIn {
            from {opacity: 0; transform: translateY(30px);}
            to {opacity: 1; transform: translateY(0);}
        }

        h1 {
            font-size: 2.3rem;
            margin-bottom: 15px;
        }

        p {
            opacity: 0.85;
            margin-bottom: 25px;
            line-height: 1.6;
        }

        .upload-box {
            margin: 20px 0;
            padding: 25px;
            border: 2px dashed rgba(255, 255, 255, 0.35);
            border-radius: 15px;
            cursor: pointer;
            transition: 0.3s;
        }

        .upload-box:hover {
            border-color: #00aaff;
            background: rgba(0, 170, 255, 0.08);
        }

        .btn {
            display: inline-block;
            margin-top: 20px;
            padding: 14px 30px;
            background: #00aaff;
            border-radius: 30px;
            text-decoration: none;
            color: white;
            font-weight: bold;
            transition: 0.3s;
        }

        .btn:hover {
            background: #0088cc;
        }
    </style>
</head>
<body>

    <div class="card">
        <h1>APK Builder</h1>
        <p>
            Buat APK kamu sendiri dengan mudah!  
            Upload file proyek (HTML / WebApp) lalu ikuti instruksi untuk mengonversi menjadi APK.
        </p>

        <div class="upload-box">
            <p>Klik / Drop file proyek di sini</p>
        </div>

        <a href="#" class="btn">Mulai Proses</a>
    </div>

</body>
</html>
