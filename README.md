HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Doctor Appointment</title>
</head>
<body>
    <h1>Welcome to Our Doctor Appointment</h1>
    <form id="appointmentForm">
        <label for="doctor">Select Doctor</label>
        <select id="doctor">
            <option value="1">Dr.John</option>
            <option value="2">Dr.Smith</option>

        </select>
        <label for="date">Select Date</label>
        <input type="date" id="date">
        <button type="submit">Book Appointment</button>>
    </form>
    <div id="availibility"></div>
    <script src="sccript.js"></script>
    
</body>
</html>

CSS

body{
    font-family:Arial, sans-serif;
    margin:0;
    padding:0;
    background-image:url('Abstract\ health\ medical\ science\ healthcare\ icon\ digital\ technology\ doctor\ concept\ modern\ innovation\,Treatment\,medicine\ on\ hi\ tech\ future\ blue\ background_\ for\ wallpaper\,\ template\,\ web\ design_\ \(1\).jpg');
    background-size:cover;
    color:white;
}
header{
    background-color: rgba(0,0,0,0.5);
    padding:20px;

}
main{
    padding:20px;
}
section{
    background-color: rgba(0,0,0,0.7);
    padding:20px;
    margin-bottom: 5px;
}
label{
    display:block;
    margin-bottom:5px;
}
input,select,button{margin-bottom: 10px;
padding:5px;
width:100%
}
button:hover{
    background-color: #45a049;
}
#errorMsg{
    color:red;
    margin-bottom: 10px;
}
   
