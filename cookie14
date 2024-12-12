<?php
$userid = "4139b31b7bab052";
setcookie("uid", $userid, time()+3600, "/", ".example.com", 0);

if (isset($_COOKIE['uid'])) {
    // Пользователь уже посещал сайт
    $userid = $_COOKIE['uid'];
    // Выполнить действия для известного пользователя
} else {
    // Пользователь новый, создать новую cookie
    $userid = generate_unique_id();
    setcookie("uid", $userid, time()+3600, "/", ".example.com", 0);
    // Выполнить действия для нового пользователя
}
?>
