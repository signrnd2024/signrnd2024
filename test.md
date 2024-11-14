<?php 
include_once('./head.php');
$_SESSION['intro'] = 'play';
?>

<div id="intro">
    <div class="video-area">
        <video autoplay muted>
            <source src="./resource/intro.mp4" type="video/mp4">
        </video>
    </div>
    <div class="ui-area">            
        <div class="col-container space-between">
            <div class="row-container space-between">
                <a href="https://signrnd.com/">
                    <img src="./resource/logo.png" alt="" srcset="">
                </a>
                <a href="#">
                    <div class="row-container gap8">

                        <div>
                            <svg width="25" height="25" viewBox="0 0 25 25" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <path d="M17.5811 13.8521V16.8521C17.5811 20.8521 15.9811 22.4521 11.9811 22.4521H8.18105C4.18105 22.4521 2.58105 20.8521 2.58105 16.8521V13.0521C2.58105 9.05215 4.18105 7.45215 8.18105 7.45215H11.1811" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                                <path d="M17.5807 13.8521H14.3807C11.9807 13.8521 11.1807 13.0521 11.1807 10.6521V7.45215L17.5807 13.8521Z" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                                <path d="M12.1807 2.45215H16.1807" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                                <path d="M7.58105 5.45215C7.58105 3.79215 8.92105 2.45215 10.5811 2.45215H13.2011" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                                <path d="M22.5815 8.45215V14.6421C22.5815 16.1921 21.3215 17.4521 19.7715 17.4521" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                                <path d="M22.5811 8.45215H19.5811C17.3311 8.45215 16.5811 7.70215 16.5811 5.45215V2.45215L22.5811 8.45215Z" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                            </svg>
                        </div>
                        <div class="ffPoppins fs16">
                            <span>COPY LINK</span>
                        </div>
                    </div>
                </a>
            </div>

            <div class="row-container space-between">
                <div class="btn-area row-container gap8">
                    <a class="btn" href="https://signrnd.com/3DARCHITECTURE/?sub=XR">XR</a>
                    <a class="btn" href="https://signrnd.com/3DARCHITECTURE/?sub=MRVR">MR·VR</a>
                    <!-- <a class="btn" href="https://signrnd.com/3DARCHITECTURE/?sub=Portfolio">PORTFOLIO</a> -->
                </div>
                <div class="row-container gap30">
                    <div class="row-container gap2">
                        <div>
                            <svg width="19" height="19" viewBox="0 0 19 19" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <path d="M9.46191 4.22168V1.22168L5.71191 4.97168L9.46191 8.72168V5.72168C11.9444 5.72168 13.9619 7.73918 13.9619 10.2217C13.9619 12.7042 11.9444 14.7217 9.46191 14.7217C6.97941 14.7217 4.96191 12.7042 4.96191 10.2217H3.46191C3.46191 13.5367 6.14691 16.2217 9.46191 16.2217C12.7769 16.2217 15.4619 13.5367 15.4619 10.2217C15.4619 6.90668 12.7769 4.22168 9.46191 4.22168Z" fill="white"/>
                            </svg>                                    
                        </div>
                        <a href="https://signrnd.com/intro.php">
                            <div class="ffPoppins fs16">
                                <span>RESTART</span>
                            </div>
                        </a>
                    </div>
                    <a href="https://signrnd.com/">
                        <div class="ffPoppins fs16">
                            <span>SKIP INTRO</span>
                        </div>
                    </a>
                </div>
            </div>
        </div>
    </div>
</div>



<?php 
include_once('./tail.php'); 
?>
