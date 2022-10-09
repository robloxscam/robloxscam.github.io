<?php
    #Config Đổi Thẻ Cào
    $cardv2 = "https://nhanthecao.vn"; #Liên Kết Đối Tác Đổi Thẻ Cào
    $apikey = "lCbNDRgPyGjFKnmYpqrefvIioJhHLaZXVkAUzTcQsxtWwMOdBESu"; #API Key Đổi Thẻ Cào
    $callback = "https://admin.trumthe5s.com/callback.php"; #Callback Trả Thẻ Tại Đây
    $type  = strtoupper($_POST['card_type']); #Loại Thẻ Cào (Thẻ Viettel, Thẻ Vinaphone, Thẻ Mobifone, Thẻ Zing, Thẻ Gate)
    $pin = $_POST['pin']; #Mã Số Thẻ Cào
    $serial  = $_POST['serial']; #Số Serial Thẻ Cào
    $amount  = $_POST['card_amount']; #Mệnh Giá Thẻ Cào
	$request_id = rand(100009, 999999); #Request ID Gửi Về Hệ Thống Đổi Thẻ Cào
	$url = ''.$cardv2.'/api/card-auto.php?type='.$type.'&menhgia='.$amount.'&seri='.$serial.'&pin='.$pin.'&APIKey='.$apikey.'&callback='.$callback.'&content='.$request_id; #Đường Dẫn Gửi Thẻ Cào
    $ch = curl_init();
    curl_setopt($ch, CURLOPT_URL, $url);
    curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
    $data = curl_exec($ch);
    curl_close($ch);
    $json = json_decode($data, true);
    #Trạng Thái Gửi Thẻ Cào
    if (isset($json['data']))
    {
    if ($json['data']['status'] == 'error') {
    #Thẻ Cào Sai Hoặc Đã Được Sử Dụng
    $vuduchoang['error'] = $json['data']['msg'];
        die(json_encode($vuduchoang));
    } else if ($json['data']['status'] == 'success') {
    #Gửi Thẻ Về Hệ Thống Đổi Thẻ Thành Công
    $vuduchoang['success'] = "Nạp Robux Thành Công. Bạn Sẽ Nhận Được Robux Khi Thẻ Đúng!";
        die(json_encode($vuduchoang));
    }
}
