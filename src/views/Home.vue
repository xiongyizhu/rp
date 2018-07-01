<template>
  <div>

  <nav class="navbar navbar-inverse">
    <div class="container">
      <div class="container-fluid">
        <!-- Brand and toggle get grouped for better mobile display -->
        <div class="navbar-header">
          <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1" aria-expanded="false">
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
          <a class="navbar-brand" href="#">Xiong Yizhu</a>
        </div>

        <!-- Collect the nav links, forms, and other content for toggling -->
        <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
          <ul class="nav navbar-nav">
            <li class="active"><a href="#">Home <span class="sr-only">(current)</span></a></li>
            <li><a href="#">About</a></li>
            <li class="dropdown">
              <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true"
                 aria-expanded="false">Dropdown <span class="caret"></span></a>
              <ul class="dropdown-menu">
                <li><a href="#">Action</a></li>
                <li><a href="#">Another action</a></li>
                <li><a href="#">Something else here</a></li>
                <li role="separator" class="divider"></li>
                <li><a href="#">Separated link</a></li>
                <li role="separator" class="divider"></li>
                <li><a href="#">One more separated link</a></li>
              </ul>
            </li>
          </ul>
          <ul class="nav navbar-nav navbar-right">
            <li><a href="#">Link</a></li>
            <li class="dropdown">
              <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true"
                 aria-expanded="false">Dropdown <span class="caret"></span></a>
              <ul class="dropdown-menu">
                <li><a href="#">Action</a></li>
                <li><a href="#">Another action</a></li>
                <li><a href="#">Something else here</a></li>
                <li role="separator" class="divider"></li>
                <li><a href="#">Separated link</a></li>
              </ul>
            </li>
          </ul>
        </div><!-- /.navbar-collapse -->
      </div><!-- /.container-fluid -->
    </div>
  </nav>

  <div class="container row-offcanvas row-offcanvas-right">
    <div class="row">
      <div class="col-sm-9">
        <p class="pull-right visible-xs">
          <button class="btn btn-primary btn-xs" data-toggle="offcanvas" @click="toggle">Toggle</button>
        </p>
        <div class="jumbotron">
          <h1>Hello, world!</h1>
          <p>这是一个示例，展示Bootstrap中offcanvas布局模式的潜力，尝试改变窗口大小，你会看到响应式布局发生的变化</p>
        </div>

        <div class="row">
          <div class="col-6 col-sm-6 col-lg-4">
            <h2>我是标题</h2>
            <p>Donec id elit non mi porta gravida at eget metus. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Etiam porta sem malesuada magna mollis euismod. Donec sed odio dui.</p>
            <a class="btn btn-default">查看详情>></a>
          </div>
          <div class="col-6 col-sm-6 col-lg-4">
            <h2>我是标题</h2>
            <p>Donec id elit non mi porta gravida at eget metus. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Etiam porta sem malesuada magna mollis euismod. Donec sed odio dui.</p>
            <a class="btn btn-default">查看详情>></a>
          </div>
          <div class="col-6 col-sm-6 col-lg-4">
            <h2>我是标题</h2>
            <p>Donec id elit non mi porta gravida at eget metus. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Etiam porta sem malesuada magna mollis euismod. Donec sed odio dui.</p>
            <a class="btn btn-default">查看详情>></a>
          </div>
          <div class="col-6 col-sm-6 col-lg-4">
            <h2>我是标题</h2>
            <p>Donec id elit non mi porta gravida at eget metus. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Etiam porta sem malesuada magna mollis euismod. Donec sed odio dui.</p>
            <a class="btn btn-default">查看详情>></a>
          </div>
          <div class="col-6 col-sm-6 col-lg-4">
            <h2>我是标题</h2>
            <p>Donec id elit non mi porta gravida at eget metus. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Etiam porta sem malesuada magna mollis euismod. Donec sed odio dui.</p>
            <a class="btn btn-default">查看详情>></a>
          </div>
          <div class="col-6 col-sm-6 col-lg-4">
            <h2>我是标题1</h2>
            <p>Donec id elit non mi porta gravida at eget metus. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Etiam porta sem malesuada magna mollis euismod. Donec sed odio dui.</p>
            <a class="btn btn-default">查看详情>></a>
          </div>

        </div>


      </div>
      <div class="col-sm-3 col-xs-6 sidebar-offcanvas" >
        <div class="list-group ">
          <a href="#" class="list-group-item active ">
            Cras justo odio
          </a>
          <a href="#" class="list-group-item">Dapibus ac facilisis in</a>
          <a href="#" class="list-group-item">Morbi leo risus</a>
          <a href="#" class="list-group-item">Porta ac consectetur ac</a>
          <a href="#" class="list-group-item">Vestibulum at eros</a>
          <a href="#" class="list-group-item">Dapibus ac facilisis in</a>
          <a href="#" class="list-group-item">Morbi leo risus</a>
          <a href="#" class="list-group-item">Porta ac consectetur ac</a>
          <a href="#" class="list-group-item">Vestibulum at eros</a>
        </div>
      </div>
    </div>
  </div>


  </div>
</template>

<script>
  export default {
    name: "Home",
    methods:{
      toggle(){
        $('.row-offcanvas').toggleClass('active')
      }
    },
    created(){

    },
    monted(){

    }
  }
</script>

<style scoped>
  @media screen and (max-width:767px){
    .row-offcanvas{
      position:relative;
      transition: all .25s ease-out;
      -o-transform: all .25s ease-out;
      -webkit-transform:  all .25s ease-out;
    }

    .row-offcanvas-right{
      right:0;
    }
    .row-offcanvas-left{
      left:0;
    }

    .row-offcanvas-right
    .sidebar-offcanvas{
      right:-50%;  /* 6 columns */
    }

    .row-offcanvas-left
    .sidebar-offcanvas{
      left:-50%;   /* 6 columns */
    }

    .row-offcanvas-right.active{
      right:50%;   /* 6 columns */
    }
    .row-offcanvas-left.active{
      left:50%;  /* 6 columns */
    }
    .sidebar-offcanvas{
      position:absolute;
      top:0;
      width:50%;   /* 6 columns */
    }
  }

</style>
