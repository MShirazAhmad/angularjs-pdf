

<body ng-app="App">

<div class="wrapper" ng-controller="DocCtrl">
  <h1>{{pdfName}}</h1>
  <ng-pdf template-url="partials/viewer.html" scale="page-fit" page=1></ng-pdf>
   <ng-pdf template-url="partials/viewer.html" scale="page-fit" page=2></ng-pdf>
  <ng-pdf template-url="partials/viewer.html" scale="page-fit" page=3></ng-pdf>

</div>
<a href="https://github.com/sayanee/angularjs-pdf"><img style="position: absolute; top: 0; right: 0; border: 0;" src="https://s3.amazonaws.com/github/ribbons/forkme_right_gray_6d6d6d.png" alt="Fork me on GitHub"></a>


<script src="js/lib/angular.min.js"></script>
<script src="js/lib/pdf.js"></script>
<script src="angular-pdf.min.js"></script>
<script src="js/app.js"></script>
<script src="js/controllers/docCtrl.js"></script>

</body>

