<!DOCTYPE html>
<html>
 <head>
    <style>
        .search-toolbar {
            display: flex;
            align-items: center;
            max-width: 500px;
            margin: 20px auto;
        }
        .search-toolbar input[type="text"] {
            flex-grow: 1;
            padding: 10px;
            font-size: 16px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .search-toolbar input[type="submit"] {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="search-toolbar">
        <form action="https://www.google.com/search" method="get" target="_blank">
            <input type="text" name="q" placeholder="Search...">
            <input type="submit" value="Search">
        </form>
    </div>
</body>
</html>
