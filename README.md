<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perfil de Usuário</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">

    <style>
         body {
            background-image: url('transferir.jpeg'); 
            background-size: cover; 
            background-position: center; 
            background-attachment: fixed; 
            background-repeat: no-repeat; 
            min-height: 100vh; 
        }

        .profile-card {
            border: 1px solid #fa0505;
            border-radius: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 50px;
            background-color: #ff7575;
            max-width: 900px;
            margin: auto;
            text-align: center;
        }

        .profile-card img {
            border-radius: 50%;
            width: 200px;
            height: 200px;
            object-fit: cover;
        }

        .social-icons a {
            margin: 0 10px;
            font-size: 1.5rem;
            color: #7e0034;
        }

        .social-icons a:hover {
            color: #007bff;
        }

        .activities-table table {
            background-color: rgba(255, 255, 255, 0.8);
            border-radius: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin-top: 30px;
        }

        .activities-table th, .activities-table td {
            text-align: center;
            padding: 10px;
        }

        .activities-table th {
            background-color: #7e0058;
            color: #d3a6a6;
        }

        .activities-table tbody tr:nth-child(odd) {
            background-color: #f7bdbd;
        }

        .activities-table tbody tr:hover {
            background-color: #6d0052;
        }
        .form-container form {
            background-color: rgba(255, 191, 239, 0.9);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .form-container .form-label {
            font-weight: bold;
        }

        .form-container input, .form-container textarea {
            border-radius: 5px;
            border: 1px solid #fabaec;
        }

    </style>
</head>

<body class="bg-light">
    <div class="container mt-5">
        <div class="profile-card">
            <img src="Imagem do WhatsApp de 2024-11-07 à(s) 12.12.29_f7ced3e4.jpg" alt="Avatar do Usuário" class="img-fluid mb-3">
            <h3>Bruna Ferraz</h3>
            <p class="text-muted">Estudante</p>
            <p>Bem-vindo ao meu perfil! Sou estudante de análise e desenvolvimento de sistemas, tenho 21 anos e moro no interior do Paraná.</p>

            <div class="social-icons">
                <a href="https://www.instagram.com/brferrasz?utm_source=ig_web_button_share_sheet&igsh=ZDNlZDc0MzIxNw==" target="_blank" title="Instagram">
                    <i class="bi bi-instagram"></i> Instagram
                </a>
                <a href="https://github.com/brferrasz" target="_blank" title="GitHub">
                    <i class="bi bi-github"></i> GitHub
            </div>
            <div class="activities-table mt-5">
                <h4 class="text-center">Atividades Recentes</h4>
                <table class="table table-bordered">
                    <thead>
                        <tr>
                            <th>#</th>
                            <th>Atividade</th>
                            <th>Data</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>1</td>
                            <td>Portifólio no GitHub</td>
                            <td>2025-03-14</td>
                        </tr>
                        <tr>
                            <td>2</td>
                            <td>Atividade prática estrutura de dados</td>
                            <td>2025-03-20</td>
                        </tr>
                    </tbody>
                </table>
            </div>
            <div class="form-container mt-5">
                <h4 class="text-center">Formulário de contato</h4>
                <form action="#" method="POST">
                    <div class="mb-3">
                        <label for="nome" class="form-label">Nome</label>
                        <input type="text" class="form-control" id="nome" name="nome" required>
                    </div>
                    <div class="mb-3">
                        <label for="email" class="form-label">Email</label>
                        <input type="email" class="form-control" id="email" name="email" required>
                    </div>
                    
                </form>
            </div>
        </div>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap-icons/font/bootstrap-icons.js"></script>
</body>

</html>
