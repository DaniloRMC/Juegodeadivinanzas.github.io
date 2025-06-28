<?php
session_start();
if (!isset($_SESSION['numero'])) {
    $_SESSION['numero'] = rand(1, 100);
}

$message = "";
if ($_SERVER['REQUEST_METHOD'] === 'POST') {
    $guess = (int)$_POST['guess'];
    if ($guess === $_SESSION['numero']) {
        $message = "¡Correcto!";
        unset($_SESSION['numero']); // Reiniciar el juego
    } else {
        $message = "Intenta de nuevo.";
    }
}
?>
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Juego de Adivinanzas</title>
</head>
<body>
    <form method="POST">
        Adivina un número del 1 al 100: <input type="number" name="guess" required>
        <button type="submit">Adivinar</button>
    </form>
    <p><?php echo $message; ?></p>
</body>
</html>
