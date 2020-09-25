

<body ng-app="App">

<div class="wrapper" ng-controller="DocCtrl">
  <h1>{{pdfName}}</h1>
<ng-pdf template-url="/partials/viewer.html" page="1"></ng-pdf>
<ng-pdf template-url="/partials/viewer.html" page="2"></ng-pdf>
<ng-pdf template-url="/partials/viewer.html" page="3"></ng-pdf>
</div>


<script src="js/lib/angular.min.js"></script>
<script src="js/lib/pdf.js"></script>
<script src="angular-pdf.min.js"></script>
<script src="js/app.js"></script>
<script src="js/controllers/docCtrl.js"></script>

</body>

