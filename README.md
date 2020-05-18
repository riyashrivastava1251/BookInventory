# BookInventory
@{
    ViewBag.Title = "Home";
}

<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=20.0">
    <title>@ViewBag.Title - Book Inventory Management System</title>
    <link href="~/Content/Site.css" rel="stylesheet" type="text/css" />
    <link href="~/Content/bootstrap.min.css" rel="stylesheet" type="text/css" />
    <script src="~/Scripts/modernizr-2.6.2.js"></script>
</head>
<body>
    <div class="navbar navbar-inverse navbar-fixed-top">
        <div class="container">
            <div class="navbar-header">
                <button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>
                @Html.ActionLink("Book Inventory Management System", "Home", "Books", new { area = "" }, new { @class = "navbar-brand" })<br />

                @Html.ActionLink("View All Books", "Index", "Books", new { area = "" }, new { @class = "navbar-brand" })<br /><b></b>

                @Html.ActionLink("Add New Book", "Create", "Books", new { area = "" }, new { @class = "navbar-brand" })


                <details>Welocme to the Book Inventory System!!!!!</details>
            </div>
            <div>Welocme to the Book Inventory System!!!!!</div>
            <div class="navbar-collapse collapse">
                <ul class="nav navbar-nav"></ul>
            </div>
        </div>
    </div>

    <div> Welcome to my book Inventory management system!!!!!!
    dfijeirrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrr</div>

    

    <script src="~/Scripts/jquery-1.10.2.min.js"></script>
    <script src="~/Scripts/bootstrap.min.js"></script>
    <p>Welocme to my inventory</p>
</body>
</html>

