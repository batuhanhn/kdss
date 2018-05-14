# kdss
<!DOCTYPE html>
<html>
<head>
      <title>Yönetim Bilişim Sistemleri</title>
      <meta charset="utf-8">
      <meta name="viewport" content="width=device-width,initial-scale=1">
      <link href="stil.css" rel="stylesheet">
      <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.0/css/bootstrap.min.css" integrity="sha384-9gVQ4dYFwwWSjIDZnLEWnxCjeSWFphJiwGPXr1jddIhOegiu1FwO5qRGvFXOdJZ4" crossorigin="anonymous">
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.0/js/bootstrap.min.js" integrity="sha384-uefMccjFJAIv6A+rW+L4AHf99KvxDjWSu1z9VI8SKNVmz4sk7buKt/6v9KI65qnm" crossorigin="anonymous"></script>
</head>
<body>

<div>
<form class="form-signin" method="POST" action="index.php">
<select class="form-control selectpicker" name="il" id="il">
  <option value="34">İstanbul</option>
  <option value="35">İzmir</option>
</select>
<select class="form-control selectpicker" name="ilce" id="ilce">
  <option value="1">Buca</option>
  <option value="2">Kadıköy</option>
</select>
<select class="form-control selectpicker" name="ay" id="ay">
  <option value="1">Ocak</option>
  <option value="2">Şubat</option>
</select>
<button class="btn-primary" type="submit">Sorgu</button>
</form>
</div>

<div  id="myDiv" class="float-right mx-auto text-white-50 animate-bottom"  >


<table class="table table-hover table-bordered text-white bg-primary  ">
        <thead>
            <tr>
                <td>İl Adı</td>
                <td>İlçe Adı</td>
				<td>Ay</td>
				<td>Toprak Çeşidi</td>
				<td>Yağış Miktarı</td>
				<td>Sıcaklık</td>
				
            </tr>
        </thead>
        <tbody>
                    </tbody>
            </table>
	  
	  
    </div>

</body>
</html>
