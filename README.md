
<!DOCTYPE html>
<head>
    <title>2. Ariketa</title>
    <style>
        body { font-family: Arial, sans-serif; }
        h1 { color: #0066cc; text-align: center; }
        nav a { margin: 10px; font-weight: bold; text-decoration: none; color: #0066cc; }
        .txiki { width: 100px; cursor: pointer; }
        nav { text-align: center;}

    </style>
    <script>
        function mostrarSeccion(seccionId) {
            const secciones = document.querySelectorAll('.section');
            secciones.forEach(section => section.style.display = 'none');
            document.getElementById(seccionId).style.display = 'block';
        }
    </script>
<body onload="mostrarSeccion('sarrera')">
</head>


    <!-- Sarrera -->
    <div id="sarrera" class="section">
        <h1>Sarrera</h1>
       
        <nav>
            <a href="2.ariketa(1).html">Lehena</a> | 
            <a href="2.ariketa(2).html">Bigarrena</a> | 
            <a href="2.ariketa(3).html">Hirugarrena</a>
        </nav>
    </div>

    

   

