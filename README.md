<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.rtl.min.css" integrity="sha384-nU14brUcp6StFntEOOEBvcJm4huWjB0OcIeQ3fltAfSmuZFrkAif0T+UtNGlKKQv" crossorigin="anonymous">
    <link rel="stylesheet" href="CSS/style.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.3.0/font/bootstrap-icons.css"> 
    <style>
body::before{
    display: block;
    content: '';
    height: 60px;
}
.bg-primary{
    background-color: #6244c5 !important;
}
.bg-warning{
    background-color: #ffc448 !important;
}
.bg-dark{
    background-color: #12141d !important;
}
.btn-warning{
    background-color: #ffc448 !important;
}
.btn-primary{
    background-color: #6244c5 !important; border: #6244c5;
}
.btn-primary:hover{
    background-color: #12141d !important;
}

    </style> 


    <title>Document</title>
</head>
<body>
    <nav class="navbar navbar-expand-md bg-light py-3 fixed-top">
        <div class="container">
            <a href="https://www.sarvinstyle.ir" class="navbar-brand">MohamadStyle</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navmenu">
                <span class="navbar-toggler-icon"></span>
            </button>
        <div class="collapse navbar-collapse" id="navmenu">
            <ul class="navbar-nav ms-auto">
             <li class="nav-item">
                <a href="#lesson" class="nav-link">آموزش ها</a>
             </li>
             <li class="nav-item">
                <a href="#aboutme" class="nav-link">درباره من</a>
             </li>
             <li class="nav-item">
                <a href="#contactme" class="nav-link">تماس با من</a>
             </li>
        </ul>
        </div>
    </div>
    </nav>
    <section class="bg-light text-center text-sm-start p-5 p-lg-0 pt-lg-2">
        <div class="container">
            <div class="d-sm-flex justify-content-between align-items-center">
                <div>
                    <h1 class="display-6">آموزش صفرتاصد</h1>
                    <div class="h1">
                        <span class="text-warning">برنامه نویسی</span> و
                        <br>طراحی سایت
                    </div>
                    <p class="lead">با آموزش های محمد استایل همراه باشید تا برنامه نویسی وطراحی سایت را از صفر به شما نشان دهم.</p>
                    <button class="btn btn-primary btn-lg">دوره های آموزشی</button>
                </div>
                <img src="IMAGES/bg.jpg" class="img-fluid w-50 d-none d-sm-block"  alt="">
            </div>
        </div>
    </section>
    <section id="aboutme" class="bg-primary text-light p-5">
        <div class="container">
            <div class="row justify-content-between align-items-center"">
                <div class="col-md">
                    <img src="IMAGES/10.jpg" alt="" class="img-fluid">
                </div>
                <div class="col-md">
                    <h2>درباره من</h2>
                    <p class="lead">سلام من محمد ساعدی هستم.یک برنامه نویس و طراح سایت با 10سال تجربه برنامه نویسی وهمچنین علاقمند ودانش آموخته ری اکت جی اس هستم.
                        </p>
                        <P>
                            در طول فعالیتم کلی مهارت و تکنولوژیهای مختلف یادگرفتم و در دوره های آموزشی ،سمینارها و کنفرانس های مختلفی شرکت کرده ام وکلی تجربه کسب کرده ام دوستدارم برای علاقه مندان آن هارا به اشتراک بزارم
                        </P>
                        <a href="" class="btn btn-light btn-lg mt-3">
                            <i class="bi bi-chevron-left"></i>بیشتر بخوانید
                        </a>
                </div>
            </div>
        </div>
    </section>
    <!-- courses -->
    <section class="p-4" id="lesson">
        <div class="container">
            <div class="row g-4 text-center">
                <div class="col-md-4">
                    <div class="card bg-primary text-light">
                        <div class="card-body text-center">
                            <div class="h1">
                                <i class="bi bi-laptop"></i>
                                <h3>مقدمات برنامه نویسی</h3>
                            </div>
                            <p class="card-text">در این مجموعه آموزش شما با مبانی برنامه نویسی را یاد خواهید گرفت
                            </p>
                            <a href="" class="btn btn-warning">مشاهده</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card bg-warning text-dark">
                        <div class="card-body text-center">
                            <div class="h1">
                                <i class="bi bi-trophy"></i>
                            </div>
                            <h3>رمز موفقیت</h3>
                            <p class="card-text">در این مجموعه آموزش شما مسیر و رمز موفقیت در برنامه نویسی را یاد خواهید گرفت
                            </p>
                            <a href="" class="btn btn-primary">مشاهده</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card bg-primary text-dark">
                        <div class="card-body text-center">
                            <div class="h1">
                                <i class=" bi bi-star"></i>
                            </div>
                            <h3>برنامه نویسی وب</h3>
                            <p class="card-text">آموزش آنلاین برنامه نویسی front-end و back-endکاملا اصولی از مبتدی
                            </p>
                            <a href="" class="btn btn-warning">مشاهده</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card bg-light">
                        <div class="card-body text-center">
                            <div class="h1">
                                <i class="bi bi-scissors"></i>
                                <h3>مقدمات برنامه نویسی</h3>
                            </div>
                            <p class="card-text">در این مجموعه آموزش شما با مبانی برنامه نویسی را یاد خواهید گرفت
                            </p>
                            <a href="" class="btn btn-warning">مشاهده</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card bg-primary text-light">
                        <div class="card-body text-center">
                            <div class="h1">
                                <i class="bi bi-pencil"></i>
                            </div>
                            <h3>رمز موفقیت</h3>
                            <p class="card-text">در این مجموعه آموزش شما مسیر و رمز موفقیت در برنامه نویسی را یاد خواهید گرفت
                            </p>
                            <a href="" class="btn btn-warning">مشاهده</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card bg-light text-dark">
                        <div class="card-body text-center">
                            <div class="h1">
                                <i class=" bi bi-star"></i>
                            </div>
                            <h3>برنامه نویسی وب</h3>
                            <p class="card-text">آموزش آنلاین برنامه نویسی front-end و back-endکاملا اصولی از مبتدی
                            </p>
                            <a href="" class="btn btn-warning">مشاهده</a>
                        </div>
                    </div>
                </div>
            </div>
            
        </div>
    </section>

    <section class="p5 ">
        <di class="container">
            <div class="row align-items-center justiy-content-beetwen">
                <div class="col-md">
                    <img src="IMAGES/blog1.jpg" class="img-fluid" alt="">
                </div>
                <div class="col-md">
                    <h2 class="text-primary">مقدمات برنامه نویسی</h2>
                    <p class="lead">در این مجموعه آموزشها،تمام نکات لازم برای شروع برنامه نویسی به زبان ساده و در مدت زمان کوتاه آموزش داده شده است</p>
                    <p>
                        با تماشا این دوره ،بیشتر نکات مهم سال اول دانشگاه را در زمان کوتاه به زبان ساده یا خواهید گرفت.ار جمله با مفاهیم مهم برنامه نویسی شامل:varriable,array,object,loop,condition آشنا خواهید شد
                    </p>
                    <a href="#" class="btn btn-light mt-3">بیشتر بخوانید
                        <i class="bi bi-chevron-left"></i>
                    </a>
                </div>
            </div>
        </di>
    </section>
    <section class="p-5">
        <div class="container">
            <div class="row align-items-center justify-content-between">
                <div class="col-md p-5">
                    <div class="col-md">
                        <h2 class="text-primary">برنامه نویسی وب</h2>
                        <p class="lead">اگر به برنامه نویسی علاقه دارید،میتوانید با ما تماشا و تمرین کلاس های آنلاین محمد استایل برنامه وب را قدم به قدم از مبتدی تا پیشرفته یا بگیرید</p>
                        <p>در این مجموعهآموزشها کرش کورس شما میتوانید در زمان خیلی کوتاه یک تکنولوژی و زبان برنامه نویسی وب را یاد بگیرید. کلیه مطالب مهم در این سری درس ها گنجانده شده است. بنابراین با تماشا و تمرین آنها شما به راحتی قادر به ساخت پروژه کامل خواهید بود</p>
                        <a href="#" class="btn btn-light mt-3">
                            <i class="bi bi-chevron-left"></i>
                        بیشتر بخوانید</a>
                    </div>
                </div>
                <div class="col-md">
                    <img src="IMAGES/image2.jpg" alt="" class="img-fluid">
                </div>
            </div>
    </section>
    
    <section id="contantme" class="bg-light p-5">
        <div class="container">
            <h2 class="text-center">
                تماس با من
            </h2>
            <div class="row align-items-center justify-conent-beetwen">
                <div class="col-md p-5">
                    <div class="mb-3">
                        <label for="exampleFormControlInput1" class="form-label">آدرس ایمیل</label>
                        <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
                      </div>
                      <div class="mb-3">
                        <label for="exampleFormControlTextarea1" class="form-label">پیام</label>
                        <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
                      </div>
                      <div class="d-grid">
                        <button class="btn btn-primary">ارسال پیام</button>
                      </div>
                </div>
                <div class="col-md p-5">
                    <div class="list-group list-group-flush">
                        <a href="#" class="list-group-item bg-light">
                            <i class="bi bi-youtube h2 x-4"></i>
                            کانال یوتیوب محمد استایل
                        </a>
                                <a href="#" class="list-group-item bg-light">
                                    <i class="bi bi-instagram h2 x-4"></i>
                                    <span class="px-3 h6">صفحه اینستاگرام محمد استایل </span>
                                    
                                </a>
                                        <a href="#" class="list-group-item bg-light">
                                            <i class="bi bi-facebook h2 x-4"></i>
                                            <span class="px-3 h6">صفحه فیسبوک محمد استایل</span>
                                            
                                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-warning text-center p-2">
        <p class="lead">copyright : &copy;2022 |MohamadStyle</p>
    </footer>





    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>

</body>
</html>
