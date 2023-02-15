<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        table {
            border: 1px solid;
        }
        table { 
	        width: 300px; 
	        border-collapse: collapse; 
	        margin:50px auto;
        }
        table{
	        border: 1px solid #050204;
	        table-layout: fixed;
	        width: 50%;
	        margin-bottom: 20px;
        }

        table th {
	        font-weight: bold;
	        padding: 5px;
	        background: #ffffff;
	        border: 1px solid #a08f8f;
        }
        table td{
	        padding: 5px 10px;
	        border: 1px solid #a58989;
	        text-align: left;
        }
        table tbody tr:nth-child(odd){
	        background: #0d925b;
        }
        table tbody tr:nth-child(even){
	        background: #11920d;
        }
        #h1{
            color: rgb(37, 209, 166);
        }
        .b1{
            background: rgb(118, 170, 34);
        }
        .b2{
            background: rgb(3, 142, 255);
        }
        .b3{
            background: rgb(100, 55, 55);
        }
        p {
            text-align: center;
            color: rgb(201, 243, 12);
        }
        #move1{
            width: 100px;
            height: 100px;
            background: rgb(28, 88, 13);
            position: relative;
            animation: mymove 5s infinite;
        }
        @keyframes mymove {
            from {left: 0px;}
            to {left: 200px;}
        }

        
    </style>

</head>
<body style="color:rgb(36, 75, 18)";>
    <h1 style="color:rgb(0, 0, 0)";>Hello ИСиП21/9</h1>
    <div id="move1"></div>
    <p style="background-color:rgb(247, 90, 0);"><b> враылвраыыаааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааааа</p>
    <ul> 
        <li>One</li>
        <li>Two</li>
        <li>Three</li>
    </ul>
    <table>
        <tr>
            <td>
                <button class="b1" onclick="alert('Hello ИСиП 21/9')"> Hello! </button>
            </td>
            <td>
                <button onclick="alert('Hello ИСиП 21/9')"> Hello! </button>
            </td>
            <td>
                <button class="b3" onclick="alert('Hello ИСиП 21/9')"> Hello! </button>
            </td>
            <td>
                <button onclick="alert('Hello ИСиП 21/9')"> Hello! </button>
            </td>
        </tr>
        <tr>
            <td>
                <button class="b2" onclick="alert('Hello ИСиП 21/9')"> Hello! </button>
            </td>
            <td>
                <button onclick="alert('Hello ИСиП 21/9')"> Hello! </button>
            </td>
            <td>
                <button id="h1" onclick="alert('Hello ИСиП 21/9')"> Hello! </button>
            </td>
            <td>
                <button onclick="alert('Hello ИСиП 21/9')"> Hello! </button>
            </td>
        </tr>
        <tr>
            <td>
                <button class="b3" onclick="alert('Hello ИСиП 21/9')"> Hello! </button>
            </td>
            <td>
                <button onclick="alert('Hello ИСиП 21/9')"> Hello! </button>
            </td>
            <td>
                <button onclick="alert('Hello ИСиП 21/9')"> Hello! </button>
            </td>
            <td>
                <button onclick="alert('Hello ИСиП 21/9')"> Hello! </button>
            </td>
        </tr>
    </table>
</body>
</html>
