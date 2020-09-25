

<body ng-app="App">

<div class="wrapper" ng-controller="DocCtrl">
<ng-pdf template-url="/partials/viewer.html" scale="page-fit" page="1"></ng-pdf>
</div>


<script src="js/lib/angular.min.js"></script>
<script src="js/lib/pdf.js"></script>
<script src="angular-pdf.min.js"></script>
<script src="js/app.js"></script>
<script src="js/controllers/docCtrl.js"></script>

</body>

