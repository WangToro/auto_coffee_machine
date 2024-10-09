# 智慧咖啡機（スマトコーヒーマシン）
這是大學畢業專題的紀錄。
これは大学で作っだ卒業研究の記録です。
以未來能當販賣商品的想法設計。
将来的に商品を販売することを考えて設計されている。

## 摘要
咖啡是許多人生活的必備品,市面上部分咖啡機是以藍芽方式連線,而連線過程需要時間,且連線距離有限、訊號也容易被阻擋,導致訊號不良的問題,加上現況下的膠囊咖啡機是使用膠囊包裝的咖啡,膠囊咖啡非常不環保,內部有些是特殊塑膠材質,塑膠的製作所排放的廢物也會汙染環境,這使得每一杯咖啡多了不必要的消耗跟污染。本次針對市面上已有的咖啡機去進行研究,分析內部機械結構對其加以改善,並增加遠端通訊控制的方式。

コーヒーは多くの人の生活必需品である。 市販されているコーヒーマシンの中には、ブルートゥース接続を採用しているものがあるが、接続処理に時間がかかり、接続距離も限られており、信号が遮断されやすく、信号不良の問題が発生しやすい。また、現在のカプセル式コーヒーマシンは、カプセルに包装されたコーヒーを使用しているが、非常に環境に優しくなく、中には特殊なプラスチック素材を内部に使用しているものもある。 そのため、一杯のコーヒーが無駄に消費され、汚染されてしまう。 本研究では、市場にある既存のコーヒーメーカーに注目し、内部機械構造を分析して改善し、遠隔通信制御方式を追加する。


## 動機
我們希望可以透過我們的研究,讓咖啡機可以以自動化的模式呈現給大家,讓使用者在煮泡咖啡過程中看到煮咖啡的流程以及它的內部結構,我們也採用仿手沖的機構,讓它不只是一台冷冰冰的機器,可以更貼近人性化,但又是自動沖泡。內部裡我們也結合了 wifi 來進行連線,讓傳輸過程中的訊號不會有被阻擋的問題,也可以節省等待的時間。

私たちの研究を通じて、コーヒーマシンを自動モードで提示することができ、ユーザーがコーヒーを淹れる過程とその内部構造を見ることができることを願っています。 また、内部には無線LANを内蔵しており、通信中に信号が遮断されることがなく、待ち時間を短縮することができます。


## 特色
我們將從無到有,打造一台手工的咖啡機,使咖啡機能與 wifi 連線並透過雲端進行資料傳輸,讓使用者可以透過手機下訂單,訂單傳送至雲端,雲端再將資料傳至咖啡機,機器就會開始製作咖啡,當咖啡製作完畢,就會回傳資料到雲端,再透過雲端傳送訊息到手機,通知使用者咖啡做好了。磨豆的部分,將馬達與手動磨豆機做結合,用 ARDUINO 去控制馬達,並結合齒輪讓磨豆能夠順利的進行。抽水的部分,使用抽水馬達來進行水的傳送,並透過從現成咖啡機上拆下的加熱機構來進行加熱,利用連通管原理和蒸氣的推進,讓熱水能夠順利的從管子流出,加熱管的部份也有考慮到食安問題,所以選擇了耐熱塑膠管。wifi 連線的部分使用 ARDUINO 的 wifi 模組來進行製作,使其可以與雲端進行資料傳輸。在機台的下方我們放置一個大水桶用來儲水。外觀使用鋁擠型做為支架,木板做整體外觀及機構,並加上防水漆來保護內外,使木板不受到水蒸氣的影響。另外 app 附有會員功能,可以紀錄使用者的使用狀況,以及個人偏好。

手作りのコーヒーマシンをゼロから作り、コーヒーマシンを無線LANに接続し、クラウドを通じてデータを送信することで、ユーザーが携帯電話から注文を行い、注文がクラウドに送信され、クラウドからコーヒーマシンにデータが送信され、コーヒーマシンがコーヒーを淹れ始め、コーヒーが出来上がるとデータがクラウドに送り返され、クラウドから携帯電話にコーヒーが出来上がったことを知らせるメッセージが送信されるようにする。 挽く部分は、モーターと手動のグラインダーを組み合わせ、ARDUINOでモーターを制御し、ギアを組み合わせることでスムーズに挽くことができる。 揚水部は揚水モーターで水を移送し、既製品のコーヒーメーカーから取り外した加熱機構で水を加熱し、連通管の原理と蒸気の推進力を利用して、お湯がスムーズに管から流れ出るようにし、加熱管は食品の安全性を考慮し、耐熱性のプラスチック管を選択した。wifi接続はARDUINOのwifiモジュールを使用し、クラウドとデータを伝送できるようにした。 wifi接続はARDUINOのwifiモジュールで行われ、クラウドとデータを送信できる。 マシンの下には水を貯めるための大きなバケツが置かれている。 外装は、支柱に押し出しアルミニウム、全体の外観と機構に木製の板、内外装を保護するために防水塗装が施され、水蒸気の影響を受けないようになっている。 また、アプリには会員機能があり、ユーザーの使用状況や個人の好みを記録することができる。

## LOGO

![slaxi](https://hackmd.io/_uploads/HJYk7BEkyg.png)


## 架構圖（架構図）

![截圖 2024-10-10 凌晨2.02.38](https://hackmd.io/_uploads/ryvww44kyg.png)

## 咖啡機本體（コーヒーマシンの本体）

![圖片 8](https://hackmd.io/_uploads/SJ9QBHNJyg.png)


### ３Ｄ圖（３D図）

![截圖 2024-10-10 凌晨2.10.11](https://hackmd.io/_uploads/HkOMKN4Jkg.png)

### 內部構造圖（内部構造図）

#### 磨豆構造（豆を潰れる構造）
![截圖 2024-10-10 凌晨2.10.04](https://hackmd.io/_uploads/ryqVKEEJJl.png)

#### 熱水出水口仿手沖迴轉構造（ドリッパー回転構造）

![截圖 2024-10-10 凌晨2.09.56](https://hackmd.io/_uploads/SJ3jFENkye.png)


## APP（アプリケーション）

### App流程圖（アプリの流れ図）

![截圖 2024-10-10 凌晨2.13.53](https://hackmd.io/_uploads/Hy71qNV1Jl.png)


### App畫面（App画面）

![截圖 2024-10-10 凌晨1.49.42](https://hackmd.io/_uploads/H11H4EVyJe.png)


## 資料庫（データベース）
 
```PHP
 <?php
session_start();
header("Content-Type: text/html; charset=utf-8");

// Database configuration
$db_server = "127.0.0.1";
$db_name = "coffee";
$db_user = "root";
$db_password = "pucsie513";

// Connect to the database
if (!@mysql_connect($db_server, $db_user, $db_password)) {
    die("Cannot connect to the database");
}

// Set the connection character set to UTF-8
mysql_query("SET NAMES utf8");

// Select the database
if (!@mysql_select_db($db_name)) {
    die("Cannot use the database");
}

// Determine the action based on the request parameter
$action = isset($_GET['action']) ? $_GET['action'] : '';

switch ($action) {
    case 'register':
        register();
        break;
    case 'login':
        login();
        break;
    case 'change_password':
        changePassword();
        break;
    case 'button_click':
        handleButtonClick();
        break;
    default:
        echo 'Invalid action';
        break;
}

// Registration function
function register() {
    $account = $_POST['account'];
    $password = $_POST['password'];
    $email = $_POST['email'];

    // Check if the account already exists
    $sql = "SELECT * FROM member WHERE account = '$account'";
    $result = mysql_query($sql);

    if (@mysql_num_rows($result) > 0) {
        echo "fail";
    } else {
        // Insert new account into the database
        $sql = "INSERT INTO member (`account`, `password`, `email`) VALUES ('$account', '$password', '$email')";
        if (mysql_query($sql)) {
            echo "success";
        } else {
            echo "Registration failed";
        }
    }
    exit;
}

// Login function
function login() {
    $account = $_POST['account'];
    $password = $_POST['password'];

    // Search the database for the account
    $sql = "SELECT * FROM member WHERE account = '$account'";
    $result = mysql_query($sql);
    $row = @mysql_fetch_row($result);

    // Verify account and password
    if ($account != null && $password != null && $row[1] == $account && $row[2] == $password) {
        echo "success";
        $_SESSION['account'] = $account; // Set session variable
    } else {
        echo 'Login failed!';
    }
    exit;
}

// Password change function
function changePassword() {
    $account = $_POST['account'];
    $repassword = $_POST['repassword'];

    // Update the password in the database
    $sql = "UPDATE member SET password = '$repassword' WHERE account = '$account'";

    if (mysql_query($sql)) {
        echo 'success';
    } else {
        echo 'fail';
    }
    exit;
}

// Button click handling function
function handleButtonClick() {
    $account = $_POST['account'];

    // Check if any account is currently active
    $status = "SELECT * FROM member WHERE start = 1";
    $result = mysql_query($status);

    if (@mysql_num_rows($result) > 0) {
        echo 'fail';
    } else {
        // Activate the account
        if ($account != null) {
            $sql = "UPDATE member SET start = 1 WHERE account = '$account'";
            mysql_query($sql);

            sleep(30); // Wait for 30 seconds

            // Deactivate the account
            $sql = "UPDATE member SET start = 0 WHERE account = '$account'";
            mysql_query($sql);
        } else {
            echo 'fail';
        }
    }
    exit;
}
?>
```


## 硬體程式碼（ハードウェアコンドルコード）

```python!

#include <stdio.h>
#include <SoftwareSerial.h>
#include <Servo.h>
#define Bean_Pin 11
#define Water_Motor_Pin 8
#define relayPin 10
int relayState = 0;
int waterState = 0;
Servo Cup_servo;

void setup() {
    Serial.begin(9600);
    pinMode(relayPin, OUTPUT);
    pinMode(Water_Motor_Pin, OUTPUT);
    pinMode(Bean_Pin, OUTPUT);
    Cup_servo.attach(9);
}

void cooking(void) {
    Serial.println("Start cooking");
    Bean();
    Water();
}

void Bean(void) {
    Serial.println("Start crack");
    digitalWrite(Bean_Pin, HIGH);
    delay(10000);
    digitalWrite(Bean_Pin, LOW);
    Serial.println("End crack");
}

void Water(void) {
    Serial.println("Start Water Motion");
    digitalWrite(Water_Motor_Pin, HIGH);
    Serial.println("Start bleed");
    delay(40000);
    digitalWrite(Water_Motor_Pin, LOW);
    Serial.println("Stop bleed");
    digitalWrite(relayPin, HIGH);
    Serial.println("Start Heating");
}

int del = 0;
int k = 0;

Cup_servo.write(0);
for (int l = 0; l < 10; l++) {
    for (int i = 0; i < 10; i++) {
        del = del + 730;
        Cup_servo.write(k);
        delay(730);
        k = k + 18;
    }
    for (int j = 0; j < 10; j++) {
        del = del + 730;
        Cup_servo.write(k);
        delay(730);
        k = k - 18;
    }
}

digitalWrite(relayPin, LOW);
Serial.println("Stop Heating");
Serial.println("Stop Water Motion");

```

實際示範影片(実際示範映像)
![截圖 2024-10-10 凌晨2.39.49](https://hackmd.io/_uploads/rJuggrVJJl.png)


