<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Add to Base</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Raleway:wght@400;700&display=swap');

        body {
            font-family: 'Raleway', sans-serif;
            background-color: #2f2e52;
            display: flex;
            flex-direction: column; /* Переключаем на вертикальное расположение */
            align-items: center; /* Выравниваем по центру */
        }

        .button {
            font-family: 'Raleway', sans-serif;
            background-color: #5c5c5c;
            border: none;
            color: white;
            padding: 15px 32px;
            text-align: center;
            display: inline-block;
            margin: 5px 4px;
            width: 100%; /* Занимают всю ширину контейнера */
            transition: all 0.5s;
            cursor: pointer;
            border-radius: 10px;
            transform: scale(1);
        }

        .form-container, .data-container {
            width: 100%; /* Занимают всю ширину экрана */
            height: 100vh;
            overflow: auto;
            padding: 20px;
            box-sizing: border-box;
        }

        .button:hover {
            background-color: #333;
            color: white;
            transform: scale(1.1);
        }

        .button:active {
            background-color: #5c5c5c;
            transform: translateY(4px);
        }

        /* Добавляем медиа-запросы для адаптации под мобильные устройства */
        @media screen and (min-width: 768px) {
            body {
                justify-content: space-evenly;
                flex-direction: row; /* Возвращаем горизонтальное расположение */
            }

            .form-container, .data-container {
                width: 45%;
            }

            .button {
                margin-left: 190px;
                width: 180px;
            }
        }

.notification {
    position: fixed;
    bottom: 10px;
    right: 10px;
    background-color: rgba(0, 0, 0, 0.8);
    color: white;
    padding: 10px 20px;
    border-radius: 5px;
    opacity: 0;
    transform: translateY(50px);
    transition: opacity 0.3s ease-in-out, transform 0.3s ease-in-out;
}

/* Изменение цвета текста в поле ввода на белый */
input[type="text"] {
                font-family: 'Raleway', sans-serif;
    color: white;
            display: block;
            margin-top: 5px;
            border: 2px solid #474747;
            border-radius: 7px;
            padding: 10px;
            width: 94%;
            background-color: #333;
            margin-left: 1px;
        }

        label {
            display: block;
            margin-top: 10px;
            color: white;
            text-align: center;
        }

        .data-block {
            text-align: center;
        }
    </style>
    <script>
    function copyKeyToClipboard(key) {
    const tempInput = document.createElement('input');
    tempInput.value = key;
    document.body.appendChild(tempInput);
    tempInput.select();
    document.execCommand('copy');
    document.body.removeChild(tempInput);

    // Отображение уведомления
    const notification = document.createElement('div');
    notification.innerText = 'Ключ был успешно скопирован!';
    notification.classList.add('notification');
    document.body.appendChild(notification);

    // Задаем анимацию появления и исчезания уведомления
    setTimeout(() => {
        notification.style.opacity = '1';
        notification.style.transform = 'translateY(0)';
    }, 10);

    setTimeout(() => {
        notification.style.opacity = '0';
        notification.style.transform = 'translateY(50px)';
    }, 2000);

    setTimeout(() => {
        document.body.removeChild(notification);
    }, 2300); // Удаляем уведомление через 2.3 секунды (анимация включая исчезание)
}

</script>
</head>
<body>
<div class="section-container">
    <h1>Database kunoi & bogdan & makar1uz</h1> 
<form method="post" action="">
    <div class="input-group">
        <label for="username">Put username:</label>
        <input type="text" name="username" required placeholder="Enter username">
    </div>
    <div class="input-group">
        <input type="submit" name="submit" value="Add to base" class="button">
    </div>
</form>
<hr>

<form method="post">
    <div class="input-group">
        <label for="deleteUsername">Delete username or key:</label>
        <input type="text" name="deleteUsername" required placeholder="Enter username or key">
    </div>
    <div class="input-group">
        <input type="submit" name="delete" value="Delete User" class="button">
    </div>
</form>
<hr>

<form method="post">
    <div class="input-group">
        <label for="reference">Enter Key or Username:</label>
        <input type="text" name="reference" required placeholder="Enter Key or Username">
    </div>
    <div class="input-group">
        <label for="newHwid">Enter New HWID:</label>
        <input type="text" name="newHwid" required placeholder="Enter New HWID">
    </div>
    <div class="input-group">
        <input type="submit" name="updateHwid" value="Update HWID" class="button">
    </div>
</form>
<hr>

<form method="post">
    <div class="input-group">
        <label for="checkKey">Enter Key:</label>
        <input type="text" name="checkKey" required placeholder="Enter Key">
    </div>
    <div class="input-group">
        <label for="checkHwid">Enter HWID:</label>
        <input type="text" name="checkHwid" required placeholder="Enter HWID">
    </div>
    <div class="input-group">
        <input type="submit" name="check" value="Check key" class="button">
    </div>
</form>
<hr>

    <?php
function generateKey() {
    $chars = 'ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789';
    $key = 'mkb_';
    for ($i = 0; $i < 10; $i++) {
        $key .= $chars[rand(0, strlen($chars)-1)];
    }
    return $key;
}

function saveData($data) {
    $file = fopen("database.txt", "a");
    fwrite($file, $data . PHP_EOL);
    fclose($file);
}
if (isset($_POST['delete']) && isset($_POST['deleteUsername'])) {
    $referenceToDelete = $_POST['deleteUsername']; // Using reference as it can be either username or key

    $fileContents = file("database.txt", FILE_IGNORE_NEW_LINES | FILE_SKIP_EMPTY_LINES);

    $foundIndex = -1; 
    foreach ($fileContents as $index => $line) {
        $lineData = explode(',', $line);
        $savedKey = trim($lineData[0]); 
        $savedUsername = trim($lineData[1]); 

        if ($savedUsername == $referenceToDelete || $savedKey == $referenceToDelete) {
            $foundIndex = $index; 
            break;
        }
    }

    if ($foundIndex != -1) { 
        unset($fileContents[$foundIndex]); 

        // Save the data back to file
        file_put_contents("database.txt", implode(PHP_EOL, $fileContents));
        echo "Key '$referenceToDelete' was deleted successfully.";
    } else { 
        echo "Reference: '$referenceToDelete' does not exist.";
    }
}

if (isset($_POST['check']) && isset($_POST['checkKey']) && isset($_POST['checkHwid'])) {
    $keyToCheck = $_POST['checkKey'];
    $hwidToCheck = $_POST['checkHwid'];

    $fileContents = file("database.txt", FILE_IGNORE_NEW_LINES | FILE_SKIP_EMPTY_LINES);

    $isValid = false;

    foreach ($fileContents as $line) {
        $lineData = explode(',', $line);
        if (trim($lineData[0]) == $keyToCheck && trim($lineData[2]) == $hwidToCheck) {
            $isValid = true;
            break;
        }
    }

    if ($isValid) {
        echo "The key and HWID are valid.";
    } else {
        echo "Invalid key or HWID.";
    }
}
if (isset($_POST['submit'])) {
    $username = $_POST['username'];
    $hwid = 'none'; 

    $dataExists = false;
    $file = fopen("database.txt", "r");
    while ($line = fgets($file)) {
        $line = trim($line);
        $lineData = explode(',', $line);
        $savedUsername = $lineData[1];
        
        if ($savedUsername == $username) {
            $dataExists = true;
            echo "Username already exists.";
            break;
        }
    }
    fclose($file);

    if (!$dataExists) {
        $key = generateKey();
        $data = $key . ',' . $username . ',' . $hwid;
        saveData($data);
        echo "Data added successfully. Your key is: $key";
    }
}

if (isset($_POST['updateHwid']) && isset($_POST['reference']) && isset($_POST['newHwid'])) {
    $reference = $_POST['reference'];
    $newHWID = $_POST['newHwid'];
    

    $fileContents = file("database.txt");
    $updatedContents = [];

    $keyFound = false;

    foreach ($fileContents as $line) {
        $lineData = explode(',', $line);
        if (trim($lineData[0]) == $keyToUpdate) {
            $keyFound = true;
            $line = $keyToUpdate . "," . $lineData[1] . "," . $newHWID . PHP_EOL;
        }
        $updatedContents[] = $line;
    }

    if ($keyFound) {
        file_put_contents("database.txt", implode("", $updatedContents));
        echo "HWID updated successfully.";
    } else {
        echo "Key not found.";
    }
}

if (isset($_POST['updateHwid']) && isset($_POST['reference']) && isset($_POST['newHwid'])) {
    $reference = $_POST['reference'];
    $newHWID = $_POST['newHwid'];

    $fileContents = file("database.txt");
    $updatedContents = [];

    $referenceFound = false;

    foreach ($fileContents as $line) {
        $lineData = explode(',', $line);
        // Проверяем, совпадает ли ключ или имя пользователя с введенным значением
        if (trim($lineData[0]) == $reference || trim($lineData[1]) == $reference) {
            $referenceFound = true;
            $line = $lineData[0] . "," . $lineData[1] . "," . $newHWID . PHP_EOL;
        }
        $updatedContents[] = $line;
    }

    if ($referenceFound) {
        file_put_contents("database.txt", implode("", $updatedContents));
        echo "HWID updated successfully.";
    } else {
        echo "Key or Username not found.";
    }
}

if(isset($_POST['keyToUpdate']) && isset($_POST['hwidToUpdate'])) {
    $keyToUpdate = $_POST['keyToUpdate'];
    $newHWID = $_POST['hwidToUpdate'];
    
    $fileContents = file("database.txt");
    $updatedContents = [];

    $keyFound = false;

    foreach($fileContents as $line) {
        $lineData = explode(',', $line);
        if(trim($lineData[0]) == $keyToUpdate) {
            $keyFound = true;
            $line = $keyToUpdate . "," . $lineData[1] . "," . $newHWID . PHP_EOL;
        }
        $updatedContents[] = $line;
    }

    if ($keyFound) {
        file_put_contents("database.txt", implode("", $updatedContents));
        echo "HWID updated successfully.";
    } else {
        echo "Key not found.";
    }
}

$file = fopen("database.txt", "r");
echo "<h2>Database:</h2>";
while ($line = fgets($file)) {
    $line = trim($line);
    $lineData = explode(',', $line);
    $key = $lineData[0];
    $username = $lineData[1];
    $hwid = $lineData[2];
    
    // Добавляем onclick атрибут, чтобы вызвать функцию копирования ключа
    echo "<p class='key-display' onclick='copyKeyToClipboard(\"$key\")'>Key: $key</p>";
    echo "<p class='username-display'>Username: $username</p>";
    echo "<p class='hwid-display'>HWID: $hwid</p>";
    echo "<hr>";
}
fclose($file);
?>
</body>
</html>