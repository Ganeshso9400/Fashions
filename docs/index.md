<!DOCTYPE html>
<html>

<head>
    <title>Bootstrap Webpage</title>

    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p"
        crossorigin="anonymous"></script>
    <script src="https://kit.fontawesome.com/0e8dcd2def.js" crossorigin="anonymous"></script>
    <!--font awesome link for icons-->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.3.0/font/bootstrap-icons.css">

    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.4/css/all.css"
        integrity="sha384-DyZ88mC6Up2uqS4h/KRgHuoeGwBcD4Ng9SiP4dIRy0EXTlnuz47vAwmeGwVChigm" crossorigin="anonymous">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
    <script src="https://kit.fontawesome.com/37fe8490f3.js" crossorigin="anonymous"></script>

    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        .left-section {
            padding: 60px 0 0 0;
            max-width: 500px;
            margin-left: 210px;
        }

        .center-section {
            background: blue;
            text-align: center;

        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
        }

        .contain {
            border-radius: 10px;
            text-align: center;
            background: white;
            padding: 20px;
        }

        .btn {
            outline-color: blue;

        }

        .card_design {
            height: 300px;
            width: 250px;
            padding: 8px;
            margin-left: 150px;
            background-color: white;
            box-shadow: none;
            border-radius: 6px;
            border: none !important;
            font-size: 15px;
            margin-top: 13px;
            /* border: 1px solid #000000; */
            display: inline-block;
        }

        .card_design_sec {
            margin-left: 50px;
            box-shadow: 1px 1px 8px grey;
            text-align: center;
            vertical-align: auto;
            padding-top: 10px;
        }

        .content {
            position: 0;
            margin-left: 250PX;
            top: 150px;
        }

        .img {
            width: 595PX;
            height: 500px;
            /* text-align: right; */
            display: block;
            margin-left: 668px;
            padding-top: 100PX;
            margin-right: auto;
            /* width: 50%; */
        }

        .content1 {
            margin-left: 10px;
            box-shadow: 1px 1px 8px grey;
            text-align: center;
            vertical-align: middle;
            padding-top: 30px;
        }

        .content3 {
            position: absolute;
            margin-left: 650PX;
            /* left: 400px; */
            top: 1075px;
            padding: 9px;
        }


        .dh {
            width: 660px;
            color: #ffff;
        }

        .ab {
            background-image: url("r.jpg");
        }
        .image{
            width: 1247px;
            height: 300px;
        }
        @media all and (max-width:1200px){
            .image{width: 600px;}
        }
    </style>
</head>

<body>

    <center>
        <div>
            <nav class="navbar-expand-lg">
                <div style="float: left;">
                    <img src="n.png" alt="No image found">
                </div>
            </nav><br><br><br><br>
            <div class="first_row">
                <div class="col-lg-6" style="display:inline-block;text-align: left;">
                    <div class="left-section">
                        <span style="font-size: 40px;text-decoration: overline;color: blue;">VR h</span>
                        <span style="font-size: 40px;color: blue">eadsets</span><br>
                        <div style="display:inline-block;text-align: left;"><b>
                                Duis aute irure dolor in reprehenderit in voluptate velit<br>
                                esse cillum dolore eu fugiat nulla pariatur. Exepteur sint<br>
                                occaecat cupidatat non provident.</b><br><br>
                        </div><br>
                        <span style="font-size:smaller;">Image by</span>
                        <span style="font-size: smaller;text-decoration:underline">Freepik</span><br><br>
                        <p class="btn btn-lg" style="background-color:blue;color: white;">&nbsp&nbsp READ MORE &nbsp</p>
                    </div>
                </div>
                <div class="col-lg-6" style="padding-right: 250px;">
                    <img src="VR.jpg" width="600px" height="450px">
                </div>
            </div>
    </center>
    <div class="clearfix"></div>
    <div class="second_row center-section" style="color: white;padding-bottom: 70px">
        <div class="row container">
            <div class="col-lg-12 ">
                <div style="display:inline-block;padding: 40px;">
                    <h1>VR's Surprising Benefits</h1>
                    sample text.Click to select the text box.Click again or double click to start the ending text.
                </div>
            </div>
            <div class="col-md-4 contain card_design card_design_sec">
                <div>
                    <img src="vricon1.png" width="60px">
                    <h4 style="color: blue;">MENTAL HEALTH</h4><br>
                    <p style="color: black;">Sample text. click to select the <br>
                        text box.CLick again or double<br>
                        click to start editing <br>
                        text. Excepteur sint occaecat <br>
                        cupidatat non proident.</p>
                    <button type="button" class="btn btn-default">more</button>
                </div>
            </div>
            <div class="col-md-4 contain card_design card_design_sec">
                <div>
                    <img src="e.JPG" width="60px">
                    <h4 style="color: blue;">REALISTIC EXPERIENCE</h4><br>
                    <p style="color: black;">Sample text. click to select the <br>
                        text box.CLick again or double<br>
                        click to start editing <br>
                        text. Excepteur sint occaecat <br>
                        cupidatat non proident.</p>
                    <button type="button" class="btn btn-default">more</button>
                </div>
            </div>
            <div class="col-md-4 contain card_design card_design_sec">
                <div>
                    <img src="r.JPG" width="60px">
                    <h4 style="color: blue;">RELAX</h4><br>
                    <p style="color: black;">Sample text. click to select the <br>
                        text box.CLick again or double<br>
                        click to start editing <br>
                        text. Excepteur sint occaecat <br>
                        cupidatat non proident.</p>
                    <button type="button" class="btn btn-default">more</button>
                </div>
            </div>
        </div>
    </div>
    <div style="padding: 60px">
        <img style=" padding-left: 280px;" src="ViR.jpg" alt="">
        <div class="content3" style="padding-top: 120px;">
            <h6>TECHNOLOGY</h6>
            <h4>Virtual Reality</h4>
            <p>There are only some symptoms such as dizziness, depression, <br>
                and collapse that appear while the VR experience. The <br>
                technology is still new and requires investigation and research. <br>
            </p>
            <p>Image by <u style="text-decoration: underline">Freepik</u></p>
            <hr>
            <p><i class="far fa-lightbulb" style="color: blue;font-size: 40px;"></i> Sample text. Click to select the
                text box. Click <br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;again or double click to start editing the <br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;text. Duis aute irure dolor.
            </p>


            <p><i class="fas fa-bullhorn" style="color: blue;font-size: 30px;"></i>Sample text. Click to select the text
                box. Click <br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; again or double click to start editing the <br>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;text. Duis aute irure dolor.
            </p>
        </div>
    </div>
    </div>
    <div style="background: rgba(184,179,179,0.4); width: 100%; height: 500px">
        <p style="text-align: center; padding-top: 50px;margin-bottom: 5px; color: royalblue; font-size: 55px;">VR's
            Surprising Benefits</p>
        <p style="text-align: center; padding-bottom: 15px; font-size: 15px;">sample text. Click to select the text box.
            Click again or double click to start editing the text.</p>
        <div style="padding-left: 305px;">

            <p class="dh"
                style="font-size: 12px; padding-left: 50px; color: black; background-color: rgba(255, 255, 255, 0.699);margin-bottom: 8px; padding-top: 18px; padding-bottom: 18px;">
                To reap the benefits of virtual reality in education. it is important for fstudents to use VR equipment
                safely. VR <br>
                users often spin around or stride blindly, ignoring their physical surroundings. A misstep could lead to
                injury. <br>
                Educators should ensure their classrooms' physical environments.
            </p>
            <p class="dh"
                style="font-size: 12px; padding-left: 50px; color: black;background-color: rgb(255, 255, 255); margin-bottom: 8px; padding-top: 18px; padding-bottom: 18px;">
                The benefits of virtual reality education are embraced by many educators, but some are still reluctant
                to use <br>
                it in their classrooms. Reasons range from high costs to pushback from school administrators. Others see
                the <br>
                value of both VR and AR as entertainment, but not as effective teaching tools in the classroom.
            </p>
            <p class="dh" class="grid-item"
                style="font-size: 12px; padding-left: 50px;background-color: rgb(77, 77, 218); padding-top: 18px; padding-bottom: 18px;">
                Before looking into some of the benefits of virtual reality in education, let's define what virtual
                reality is and how <br>
                it differs from augmented reality. AR is used on a smart device to project a layer of educational text
                and lesson- <br>
                appropriate content on top of a user's actual surroundings.
            </p>
        </div>
    </div>

    </div>



    <section id="learn" class="p-5">
        <div class="container">
            <div class="row align-items-center justify-content-between">

                <div class="col-md p-5" style="margin-left: 100px;">
                    <h5 class="text-primary">TECHNOLOGY</h5>
                    <p style="font-size: 27px;">IS VR BAD FOR YOUR <br>BRAIN?</p>
                    <p>There is no scientific evidence that Virtual Reality can <br>
                        provoke constant brain damage to adults and kids. <br>
                        There are only some symptoms such as dizziness, <br>
                        depression, and collapse that appear while the <br>
                        VR experience. The technology is still new and requires <br>
                        investigation and research.
                    </p>
                    <p>
                        <b>Bibendum neque egestas congue quisque egestas <br>
                            diam in arcu. Euismod in pellentesque massa <br>
                            placerat duis ultricies lacus sed turpis. Sit amet <br>
                            consectetur adipiscing elit.</b>
                    </p>
                    <p>Image by <u style="text-decoration: underline" class="text-primary">Freepik</u></p>
                    <a href="#" class="btn btn-light">See More</a>
                </div>
                <div class="col-md">
                    <img src="VRbrain.jpg" class="img-fluid" alt="image not found" />
                </div>
            </div>
        </div>
    </section>

    <div class="col-lg-12">
        <img src="VRL.jpg" class="image">
    </div>


    <section id="learn" class="p-5">
        <div class="container">
            <div class="row align-items-center justify-content-between">
                <div class="col-md" style="padding-left: 130px;">
                    <p style="font-size: 25px;color: blue;"><b>10 Key Benefits of VR in <br>Education</b></p>
                    <p>
                        The prinicipal reason we continue to adapt and evolve our<br>
                        business model is to ensure that we are meeting our customer's<br>
                        expectations. One example of this has been to use modern<br>
                        technology and the introduction of the real time tracking our<br>
                        teams using GPS. This ensures our customers get the time they<br>
                        have paid for has been spent at our customer's homes since this<br>
                        is the most common problem within our industry.<br>
                    </p>
                </div>
                <div class="col-md p-5">
                    <p style="font-size: 35px;color: blue;font-family: 'Courier New', Courier, monospace;">Experts
                        reveal four<br>surprising health<br>benefits of VR<br>gaming</p><br>
                    <b>SAMPLE HEADLINE</b>
                </div>
            </div>
        </div>
    </section>
    <div style="color: white; height: 180px;width: 100%;text-align: center; background-color: rgb(77, 77, 218);">
        <p style="padding-top: 25px; font-size: 40px;">FOLLOW US!</p>
        <i style="padding: 4px;" class="fab fa-facebook-f"></i>
        <i style="padding: 4px;" class="fab fa-twitter"></i>
        <i style="padding: 4px;" class="fab fa-instagram"></i>
        <i style="padding: 4px;" class="fas fa-font"></i>
        <i style="padding: 4px;" class="fab fa-pinterest-p"></i>
        <p
            style="border: solid; color: white; width: 65px; height: 7px; background-color: white; margin-left: 600px; margin-top: 10px;">
        </p>



    </div>
    <div style="background: rgb(53, 52, 52);width: 100%; height: 180px;">
        <div style="text-align: center;">
            <p style="color: white; padding-top: 25px; margin-bottom: 50px;">Sample text. Click to select the text box.
                Click again or double <br>click to start editing the text.</p>
            <!-- <p style="color: white; "></p> -->
            <p><u style="color: cornflowerblue;"> Website Templates</u><u style="color: white; text-decoration: none;">
                    created with</u> <u style="color: cornflowerblue;">Website Builder Software.</u></p>
        </div>
    </div>


    </div>

</body>

</html>
