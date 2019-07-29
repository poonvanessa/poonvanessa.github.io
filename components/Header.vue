<template>
<head>
   <!-- Global site tag (gtag.js) - Google Analytics -->
   <script async src="https://www.googletagmanager.com/gtag/js?id=UA-144686027-1"></script>
   <script>
      window.dataLayer = window.dataLayer || [];
      function gtag() { dataLayer.push(arguments); }
      gtag('js', new Date());

      gtag('config', 'UA-144686027-1');
   </script>

   <meta charset="utf-8">
   <meta http-equiv="X-UA-Compatible" content="IE=Edge">
   <meta name="viewport" content="width=device-width, initial-scale=1">
   <meta name="keywords" content="">
   <meta name="description" content="">

   <!-- Site title
   ================================================== -->
   <title>{{ title }}</title>

   <!-- Bootstrap CSS
   ================================================== -->
   <link rel="stylesheet" href="css/bootstrap.min.css">

   <!-- Animate CSS
   ================================================== -->
   <link rel="stylesheet" href="css/animate.min.css">

   <!-- Font Icons CSS
   ================================================== -->
   <link rel="stylesheet" href="css/font-awesome.min.css">
   <link rel="stylesheet" href="css/ionicons.min.css">

   <!-- Main CSS
   ================================================== -->
   <link rel="stylesheet" href="css/style.css">

   <!-- Google web font 
   ================================================== -->
   <link href='https://fonts.googleapis.com/css?family=Source+Sans+Pro:400,700,300' rel='stylesheet' type='text/css'>

   <!-- Vue js
   ================================================== -->
    <script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
</head>

</template>

<script>
export default {
  data() {
    return {
      title: 'What's next?'
    }
  }
}
</script>