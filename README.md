<!DOCTYPE html>
<html>

<head>
    <title>Ipsoom Center - Silex template</title>
    <meta charset="UTF-8">
    <meta name="generator" content="Silex v2.2.7">
    <!-- leave this for stats -->
    <script type="text/javascript" src="//editor.silex.me/static/2.7/jquery.js" data-silex-static=""></script>
    <meta class="CryptoPluginExtensionLoaded">
    <meta class="CryptoPluginExtensionLoaded">
    <script type="text/javascript" src="//editor.silex.me/static/2.7/jquery-ui.js" data-silex-static=""></script>

    <script type="text/javascript" src="//editor.silex.me/static/2.7/pageable.js" data-silex-static=""></script>
    <script type="text/javascript" src="//editor.silex.me/static/2.7/front-end.js" data-silex-static=""></script>
    <!-- Normalize -->
    <link href="//editor.silex.me/static/2.7/normalize.css" rel="stylesheet" data-silex-static="">
    <!-- Silex style -->
    <link href="//editor.silex.me/static/2.7/front-end.css" rel="stylesheet" data-silex-static="">

    <style type="text/css" class="silex-style">
        @import url('//fonts.googleapis.com/css?family=Roboto:100');
        .logo .title {
            color: #FF9900;
        }
        
        .logo .normal {
            color: #FEFFFD;
            font-family: 'Roboto', sans-serif;
            font-size: 60px;
            line-height: 25px;
            min-height: 125px;
            text-transform: uppercase;
        }
        
        .nav .normal {
            color: #FEFFFD;
            font-family: 'Roboto', sans-serif;
            font-size: 18px;
            line-height: 45px;
            text-transform: uppercase;
            z-index: 1;
        }
        
        .nav-mark {
            border-bottom: 1px solid #000000;
            transition: border .2s ease-out, background-color .2s ease-out;
        }
        
        .nav-mark:hover {
            border-bottom: 1px solid #FF9900;
        }
        
        .nav-mark.page-link-active {
            background-color: #FF9900;
        }
        /* home */
        
        .sub-nav.page-link-active {
            width: 250px;
            box-shadow: 0 1px 10px black;
        }
        
        .sub-nav {
            transition: all .15s ease-out;
            color: #FEFFFD;
            font-family: 'Roboto', sans-serif;
            font-size: 25px;
            line-height: 5px;
            text-transform: uppercase;
            z-index: 1;
        }
        
        .sub-nav .heading1 {
            font-size: 40px;
        }
        
        .normal,
        .heading1 {
            color: #FEFFFD;
            font-weight: 200;
            line-height: 20px;
        }
        
        .white-bg .heading2,
        .white-bg .normal {
            color: black;
        }
        
        .white-bg .heading2 {
            font-family: 'Roboto', sans-serif;
            font-weight: 100;
            font-size: 40px;
            text-transform: capitalize;
            line-height: 0px;
        }
        
        .white-bg .heading2:first-letter {
            background-color: #FF9900;
            color: #FEFFFD;
            padding: 0 10px;
            margin-right: 2px;
        }
        
        .white-bg .normal {
            font-size: 15px;
            font-family: Arial, sans-serif;
            line-height: 20px;
        }
        
        .button-read-more .normal {
            font-family: 'Roboto', sans-serif;
            font-weight: 100;
            text-transform: capitalize;
            line-height: 30px;
        }
    </style>
    <script type="text/javascript" class="silex-script"></script>
    <meta name="publicationPath" content="/api/1.0/github/exec/put/silex-templates/wip/ipsoom">
    <style class="silex-inline-styles" type="text/css">
        .silex-id-1439554967896-66 {
            left: 0px;
            top: 0px;
            background-color: rgb(0, 0, 0);
            border-top-color: rgb(0, 0, 0);
            border-right-color: rgb(0, 0, 0);
            border-bottom-color: rgb(0, 0, 0);
            border-left-color: rgb(0, 0, 0);
        }
        
        .silex-id-1490693608162-3 {
            background-color: transparent;
            top: 0px;
            left: 0px;
            min-width: 960px;
        }
        
        .silex-id-1490693608161-2 {
            min-height: 138px;
            background-color: transparent;
            top: 15px;
            left: 647px;
            width: 960px;
        }
        
        .silex-id-1439554967492-62 {
            width: 77px;
            top: 84px;
            left: 278px;
            box-sizing: content-box;
            min-height: 45px;
        }
        
        .silex-id-1439554967286-60 {
            width: 133px;
            top: 84px;
            left: 377px;
            box-sizing: content-box;
            min-height: 36px;
        }
        
        .silex-id-1439554966975-57 {
            width: 133px;
            top: 83px;
            left: 529px;
            box-sizing: content-box;
            min-height: 37px;
        }
        
        .silex-id-1439554966767-55 {
            width: 128px;
            top: 83px;
            left: 681px;
            box-sizing: content-box;
            min-height: 45px;
        }
        
        .silex-id-1439554966563-53 {
            width: 95px;
            top: 83px;
            left: 829px;
            box-sizing: content-box;
            min-height: 45px;
        }
        
        .silex-id-1490693355800-0 {
            width: 218px;
            min-height: 106px;
            top: 19px;
            left: 8px;
        }
        
        .silex-id-1490693798023-5 {
            background-color: transparent;
            top: 178px;
            left: 5px;
            min-width: 960px;
        }
        
        .silex-id-1490693798022-4 {
            min-height: 474px;
            background-color: transparent;
            top: 15px;
            left: 647px;
            width: 960px;
        }
        
        .silex-id-1439554966458-52 {
            width: 960px;
            top: -14px;
            left: 0px;
            box-sizing: content-box;
            background-color: rgb(0, 0, 0);
            min-height: 483px;
        }
        
        .silex-id-1439554966357-51 {
            width: 232px;
            top: 163px;
            left: 0px;
            box-sizing: content-box;
            border-top-color: rgb(255, 255, 255);
            border-right-color: rgb(255, 255, 255);
            border-bottom-color: rgb(255, 255, 255);
            border-left-color: rgb(255, 255, 255);
            border-top-width: 0px;
            border-right-width: 3px;
            border-bottom-width: 0px;
            border-left-width: 0px;
            border-top-style: solid;
            border-right-style: solid;
            border-bottom-style: solid;
            border-left-style: solid;
            background-color: rgb(102, 88, 71);
            min-height: 158px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554966357-51 {
                top: 0px;
                left: 93px;
                width: 234px;
                min-height: 158px;
            }
        }
        
        .silex-id-1439554966255-50 {
            width: 183px;
            top: 22px;
            left: 45px;
            box-sizing: content-box;
            min-height: 118px;
        }
        
        .silex-id-1439554966154-49 {
            width: 232px;
            top: 5px;
            left: 0px;
            box-sizing: content-box;
            border-top-color: rgb(255, 255, 255);
            border-right-color: rgb(255, 255, 255);
            border-bottom-color: rgb(255, 255, 255);
            border-left-color: rgb(255, 255, 255);
            border-top-width: 0px;
            border-right-width: 3px;
            border-bottom-width: 0px;
            border-left-width: 0px;
            border-top-style: solid;
            border-right-style: solid;
            border-bottom-style: solid;
            border-left-style: solid;
            background-color: rgb(255, 153, 0);
            min-height: 158px;
        }
        
        .silex-id-1439554966050-48 {
            width: 183px;
            top: 17px;
            left: 45px;
            box-sizing: content-box;
            min-height: 104px;
        }
        
        .silex-id-1439554965843-46 {
            width: 232px;
            top: 321px;
            left: 0px;
            box-sizing: content-box;
            border-top-color: rgb(255, 255, 255);
            border-right-color: rgb(255, 255, 255);
            border-bottom-color: rgb(255, 255, 255);
            border-left-color: rgb(255, 255, 255);
            border-top-width: 0px;
            border-right-width: 3px;
            border-bottom-width: 0px;
            border-left-width: 0px;
            border-top-style: solid;
            border-right-style: solid;
            border-bottom-style: solid;
            border-left-style: solid;
            background-color: rgb(61, 54, 45);
            min-height: 158px;
        }
        
        .silex-id-1439554965740-45 {
            width: 183px;
            top: 22px;
            left: 45px;
            box-sizing: content-box;
            min-height: 104px;
        }
        
        .silex-id-1439554965638-44 {
            width: 726px;
            top: 5px;
            left: 232px;
            box-sizing: content-box;
            background-image: url('../../../../../../../libs/templates/silex-templates/ipsoom/assets/UJO0jYLtRte4qpyA37Xu_9X6A7388.jpg');
            background-color: transparent;
            background-size: cover;
            min-height: 474px;
        }
        
        .silex-id-1439554965536-43 {
            width: 726px;
            top: 6px;
            left: 233px;
            box-sizing: content-box;
            background-image: url('../../../../../../../libs/templates/silex-templates/ipsoom/assets/8bc72ed7.jpg');
            background-color: transparent;
            background-size: cover;
            min-height: 474px;
        }
        
        .silex-id-1439554965947-47 {
            width: 726px;
            top: -10px;
            left: 232px;
            box-sizing: content-box;
            background-image: url('../../../../../../../libs/templates/silex-templates/ipsoom/assets/xpdPwXTASnOUXFpIPgDs_IMG_1460_edt.jpg');
            background-color: transparent;
            background-size: cover;
            min-height: 474px;
        }
        
        .silex-id-1490693931165-7 {
            background-color: transparent;
            top: 686px;
            left: 0px;
            min-width: 960px;
        }
        
        .silex-id-1490693931163-6 {
            min-height: 703px;
            background-color: transparent;
            top: 15px;
            left: 545px;
            width: 960px;
        }
        
        .silex-id-1439554965432-42 {
            width: 960px;
            top: -9px;
            left: 0px;
            box-sizing: content-box;
            background-color: rgb(254, 255, 253);
            min-height: 309px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554965432-42 {
                top: 141px;
                left: 11px;
                width: 423px;
                min-height: 979px;
            }
        }
        
        .silex-id-1439554965331-41 {
            width: 290px;
            top: 26px;
            left: 37px;
            box-sizing: content-box;
            border-top-width: 0px;
            border-right-width: 1px;
            border-bottom-width: 0px;
            border-left-width: 0px;
            border-top-style: solid;
            border-right-style: solid;
            border-bottom-style: solid;
            border-left-style: solid;
            border-top-color: rgb(102, 88, 71);
            border-right-color: rgb(102, 88, 71);
            border-bottom-color: rgb(102, 88, 71);
            border-left-color: rgb(102, 88, 71);
            background-color: transparent;
            min-height: 254px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554965331-41 {
                top: 32px;
                left: 10px;
                width: 402px;
                min-height: 262px;
            }
        }
        
        .silex-id-1439554965129-39 {
            width: 283px;
            top: -6px;
            left: 0px;
            box-sizing: content-box;
            min-height: 60px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554965129-39 {
                top: 91px;
                left: 10px;
                width: 382px;
                min-height: 67px;
            }
        }
        
        .silex-id-1439554965028-38 {
            width: 260px;
            top: 66px;
            left: 0px;
            box-sizing: content-box;
            border-top-width: 5px;
            border-right-width: 5px;
            border-bottom-width: 5px;
            border-left-width: 5px;
            border-top-style: solid;
            border-right-style: solid;
            border-bottom-style: solid;
            border-left-style: solid;
            border-top-color: rgb(0, 0, 0);
            border-right-color: rgb(0, 0, 0);
            border-bottom-color: rgb(0, 0, 0);
            border-left-color: rgb(0, 0, 0);
            border-image-source: initial;
            border-image-slice: initial;
            border-image-width: initial;
            border-image-outset: initial;
            border-image-repeat: initial;
            background-image: url('../../../../../../../libs/templates/silex-templates/ipsoom/assets/wood.jpg');
            background-color: rgb(0, 0, 0);
            background-size: cover;
            min-height: 94px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554965028-38 {
                top: 158px;
                left: 5px;
                width: 382px;
                min-height: 94px;
            }
        }
        
        .silex-id-1439554965230-40 {
            width: 266px;
            top: 169px;
            left: 3px;
            box-sizing: content-box;
            min-height: 91px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554965230-40 {
                top: 0px;
                left: 10px;
                width: 382px;
                min-height: 91px;
            }
        }
        
        .silex-id-1439554964925-37 {
            width: 290px;
            top: 26px;
            left: 345px;
            box-sizing: content-box;
            border-top-width: 0px;
            border-right-width: 1px;
            border-bottom-width: 0px;
            border-left-width: 0px;
            border-top-style: solid;
            border-right-style: solid;
            border-bottom-style: solid;
            border-left-style: solid;
            border-top-color: rgb(102, 88, 71);
            border-right-color: rgb(102, 88, 71);
            border-bottom-color: rgb(102, 88, 71);
            border-left-color: rgb(102, 88, 71);
            background-color: transparent;
            min-height: 254px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554964925-37 {
                top: 359px;
                left: 10px;
                width: 402px;
                min-height: 262px;
            }
        }
        
        .silex-id-1439554964619-34 {
            width: 283px;
            top: -6px;
            left: 0px;
            box-sizing: content-box;
            min-height: 60px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554964619-34 {
                top: 196px;
                left: 10px;
                width: 382px;
                min-height: 66px;
            }
        }
        
        .silex-id-1439554964822-36 {
            width: 260px;
            top: 66px;
            left: 0px;
            box-sizing: content-box;
            border-top-width: 5px;
            border-right-width: 5px;
            border-bottom-width: 5px;
            border-left-width: 5px;
            border-top-style: solid;
            border-right-style: solid;
            border-bottom-style: solid;
            border-left-style: solid;
            border-top-color: rgb(0, 0, 0);
            border-right-color: rgb(0, 0, 0);
            border-bottom-color: rgb(0, 0, 0);
            border-left-color: rgb(0, 0, 0);
            border-image-source: initial;
            border-image-slice: initial;
            border-image-width: initial;
            border-image-outset: initial;
            border-image-repeat: initial;
            background-image: url('../../../../../../../libs/templates/silex-templates/ipsoom/assets/night.jpg');
            background-color: rgb(0, 0, 0);
            background-size: cover;
            min-height: 94px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554964822-36 {
                top: 0px;
                left: 5px;
                width: 382px;
                min-height: 94px;
            }
        }
        
        .silex-id-1439554964720-35 {
            width: 266px;
            top: 169px;
            left: 3px;
            box-sizing: content-box;
            min-height: 91px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554964720-35 {
                top: 104px;
                left: 10px;
                width: 382px;
                min-height: 91px;
            }
        }
        
        .silex-id-1439554964518-33 {
            width: 290px;
            top: 26px;
            left: 656px;
            box-sizing: content-box;
            border-top-color: rgb(102, 88, 71);
            border-right-color: rgb(102, 88, 71);
            border-bottom-color: rgb(102, 88, 71);
            border-left-color: rgb(102, 88, 71);
            background-color: transparent;
            min-height: 254px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554964518-33 {
                top: 685px;
                left: 11px;
                width: 414px;
                min-height: 262px;
            }
        }
        
        .silex-id-1439554964214-30 {
            width: 283px;
            top: -6px;
            left: 0px;
            box-sizing: content-box;
            min-height: 60px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554964214-30 {
                top: 196px;
                left: 10px;
                width: 394px;
                min-height: 66px;
            }
        }
        
        .silex-id-1439554964416-32 {
            width: 260px;
            top: 66px;
            left: 0px;
            box-sizing: content-box;
            border-top-width: 5px;
            border-right-width: 5px;
            border-bottom-width: 5px;
            border-left-width: 5px;
            border-top-style: solid;
            border-right-style: solid;
            border-bottom-style: solid;
            border-left-style: solid;
            border-top-color: rgb(0, 0, 0);
            border-right-color: rgb(0, 0, 0);
            border-bottom-color: rgb(0, 0, 0);
            border-left-color: rgb(0, 0, 0);
            border-image-source: initial;
            border-image-slice: initial;
            border-image-width: initial;
            border-image-outset: initial;
            border-image-repeat: initial;
            background-image: url('../../../../../../../libs/templates/silex-templates/ipsoom/assets/bench.jpg');
            background-color: rgb(0, 0, 0);
            background-size: cover;
            min-height: 94px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554964416-32 {
                top: 0px;
                left: 5px;
                width: 394px;
                min-height: 94px;
            }
        }
        
        .silex-id-1439554964315-31 {
            width: 266px;
            top: 169px;
            left: 3px;
            box-sizing: content-box;
            min-height: 91px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554964315-31 {
                top: 104px;
                left: 10px;
                width: 394px;
                min-height: 91px;
            }
        }
        
        .silex-id-1439554964011-28 {
            width: 225px;
            top: 334px;
            left: 41px;
            box-sizing: content-box;
            min-height: 61px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554964011-28 {
                top: 1603px;
                left: 11px;
                width: 423px;
                min-height: 90px;
            }
        }
        
        .silex-id-1439554963909-27 {
            width: 47px;
            top: 327px;
            left: 310px;
            box-sizing: content-box;
            min-height: 68px;
        }
        
        .silex-id-1439554964112-29 {
            width: 592px;
            top: 333px;
            left: 342px;
            box-sizing: content-box;
            min-height: 111px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554964112-29 {
                top: 1183px;
                left: 57px;
                width: 331px;
                min-height: 172px;
            }
        }
        
        .silex-id-1439554963809-26 {
            width: 47px;
            top: 399px;
            left: 647px;
            box-sizing: content-box;
            min-height: 68px;
        }
        
        .silex-id-1439554963707-25 {
            width: 280px;
            top: 469px;
            left: 25px;
            box-sizing: content-box;
            background-color: transparent;
            min-height: 215px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554963707-25 {
                top: 1241px;
                left: 11px;
                width: 423px;
                min-height: 215px;
            }
        }
        
        .silex-id-1439554963605-24 {
            width: 276px;
            top: 14px;
            left: 14px;
            box-sizing: content-box;
            min-height: 147px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554963605-24 {
                top: 5px;
                left: 11px;
                width: 401px;
                min-height: 160px;
            }
        }
        
        .silex-id-1439554963502-23 {
            width: 113px;
            top: 166px;
            left: 16px;
            box-sizing: content-box;
            background-color: rgba(102, 88, 71, 1);
            min-height: 34px;
        }
        
        .silex-id-1439554963400-22 {
            width: 280px;
            top: 469px;
            left: 332px;
            box-sizing: content-box;
            background-color: transparent;
            min-height: 215px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554963400-22 {
                top: 1456px;
                left: 11px;
                width: 423px;
                min-height: 215px;
            }
        }
        
        .silex-id-1439554963298-21 {
            width: 276px;
            top: 14px;
            left: 14px;
            box-sizing: content-box;
            min-height: 147px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554963298-21 {
                top: 5px;
                left: 11px;
                width: 401px;
                min-height: 160px;
            }
        }
        
        .silex-id-1439554963198-20 {
            width: 113px;
            top: 166px;
            left: 16px;
            box-sizing: content-box;
            background-color: rgb(102, 88, 71);
            min-height: 34px;
        }
        
        .silex-id-1439554963096-19 {
            width: 280px;
            top: 469px;
            left: 639px;
            box-sizing: content-box;
            background-color: transparent;
            min-height: 215px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554963096-19 {
                top: 1671px;
                left: 11px;
                width: 423px;
                min-height: 215px;
            }
        }
        
        .silex-id-1439554962995-18 {
            width: 276px;
            top: 14px;
            left: 14px;
            box-sizing: content-box;
            min-height: 147px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554962995-18 {
                top: 5px;
                left: 11px;
                width: 401px;
                min-height: 160px;
            }
        }
        
        .silex-id-1439554962893-17 {
            width: 113px;
            top: 166px;
            left: 16px;
            box-sizing: content-box;
            background-color: rgba(102, 88, 71, 1);
            min-height: 34px;
        }
        
        .silex-id-1490694258064-17 {
            background-color: transparent;
            top: 171px;
            left: 0px;
            border-color: #000000;
            min-width: 960px;
        }
        
        .silex-id-1490694258062-16 {
            min-height: 744px;
            background-color: transparent;
            border-color: #000000;
            top: 15px;
            left: 329px;
            width: 960px;
        }
        
        .silex-id-1492776401689-1 {
            width: 456px;
            height: 587px;
            background-color: transparent;
            top: 83px;
            left: 1px;
        }
        
        .silex-id-1492776672785-2 {
            height: 571px;
            width: 472px;
            background-color: transparent;
            top: 91px;
            left: 487px;
            border-width: 1px 1px 1px 1px;
            border-style: solid;
            border-color: #ffffff;
        }
        
        .silex-id-1490694152451-11 {
            background-color: transparent;
            top: 433px;
            left: NaNpx;
            min-width: 960px;
        }
        
        .silex-id-1490694152449-10 {
            min-height: 236px;
            background-color: transparent;
            top: 15px;
            left: 545px;
            width: 960px;
        }
        
        .silex-id-1439554961635-5 {
            width: 817px;
            top: 31px;
            left: 2px;
            box-sizing: content-box;
            min-height: 189px;
        }
        
        .silex-id-1490701849669-19 {
            background-color: transparent;
            top: 159px;
            left: 0px;
            min-width: 960px;
            background-image: url('../../../../../../../libs/templates/silex-templates/ipsoom/assets/UJO0jYLtRte4qpyA37Xu_9X6A7388.jpg');
            background-size: cover;
            background-position: center center;
        }
        
        .silex-id-1490701849668-18 {
            min-height: 480px;
            background-color: transparent;
            top: 15px;
            left: 545px;
            width: 960px;
        }
        
        .silex-id-1490694217944-13 {
            background-color: transparent;
            top: 171px;
            left: 0px;
        }
        
        .silex-id-1490694217944-12 {
            min-height: 236px;
            background-color: transparent;
        }
        
        .silex-id-1439554961432-3 {
            width: 817px;
            top: 31px;
            left: 2px;
            box-sizing: content-box;
            min-height: 189px;
        }
        
        .silex-id-1490701905049-21 {
            background-color: transparent;
            top: 100px;
            left: NaNpx;
            background-image: url('../../../../../../../libs/templates/silex-templates/ipsoom/assets/nQZcA7PRTyuduZPSZQ88_wanderlust.jpg');
            background-size: cover;
            background-position: center center;
        }
        
        .silex-id-1490701905043-20 {
            min-height: 480px;
            background-color: transparent;
        }
        
        .silex-id-1490694237194-15 {
            background-color: transparent;
            top: 171px;
            left: 0px;
            min-width: 960px;
        }
        
        .silex-id-1490694237193-14 {
            min-height: 232px;
            background-color: transparent;
            top: 15px;
            left: 545px;
            width: 960px;
        }
        
        .silex-id-1439554961331-2 {
            width: 817px;
            top: 31px;
            left: 2px;
            box-sizing: content-box;
            min-height: 189px;
        }
        
        .silex-id-1490701944668-23 {
            background-color: transparent;
            top: 100px;
            left: NaNpx;
            background-image: url('../../../../../../../libs/templates/silex-templates/ipsoom/assets/xpdPwXTASnOUXFpIPgDs_IMG_1460_edt.jpg');
            background-size: cover;
            background-position: bottom center;
        }
        
        .silex-id-1490701944667-22 {
            min-height: 480px;
            background-color: transparent;
        }
        
        .silex-id-1490694042605-9 {
            background-color: transparent;
            top: 931px;
            left: 0px;
        }
        
        .silex-id-1490694042604-8 {
            min-height: 269px;
            background-color: transparent;
        }
        
        .silex-id-1439554962589-14 {
            width: 88px;
            top: 88px;
            left: 834px;
            min-height: 37px;
        }
        
        .silex-id-1439554962691-15 {
            width: 264px;
            top: 85px;
            left: 37px;
            box-sizing: content-box;
            min-height: 67px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554962691-15 {
                top: 2000px;
                left: 13px;
                width: 419px;
                min-height: 125px;
            }
        }
        
        .silex-id-1439554962488-13 {
            width: 40px;
            top: 86px;
            left: 771px;
            min-height: 40px;
        }
        
        .silex-id-1439554962386-12 {
            width: 25px;
            top: 139px;
            left: 663px;
            box-sizing: content-box;
            min-height: 34.5676px;
        }
        
        .silex-id-1439554962283-11 {
            width: 240px;
            top: 127px;
            left: 698px;
            box-sizing: content-box;
            min-height: 52px;
        }
        
        @media only screen and (max-width: 480px),
        only screen and (max-device-width: 480px) {
            .silex-id-1439554962283-11 {
                top: 2129px;
                left: 1px;
                width: 240px;
                min-height: 38px;
            }
        }
        
        .silex-id-1439554962181-10 {
            width: 102px;
            top: 136px;
            left: 539px;
            box-sizing: content-box;
            min-height: 45px;
        }
        
        .silex-id-1439554962078-9 {
            width: 133px;
            top: 136px;
            left: 400px;
            box-sizing: content-box;
            min-height: 45px;
        }
        
        .silex-id-1439554961964-8 {
            width: 146px;
            top: 136px;
            left: 247px;
            box-sizing: content-box;
            min-height: 45px;
        }
        
        .silex-id-1439554961840-7 {
            width: 134px;
            top: 136px;
            left: 107px;
            box-sizing: content-box;
            min-height: 45px;
        }
        
        .silex-id-1439554961739-6 {
            width: 65px;
            top: 136px;
            left: 37px;
            box-sizing: content-box;
            min-height: 45px;
        }
        
        .silex-id-1439554962792-16 {
            width: 600px;
            top: 208px;
            left: 180px;
            box-sizing: content-box;
            background-color: transparent;
            min-height: 50px;
        }
    </style>




























    <script type="text/javascript" class="silex-json-styles">
        [{"desktop":{"silex-id-1439554967896-66":{"left":"0px","top":"0px","background-color":"rgb(0, 0, 0)","border-top-color":"rgb(0, 0, 0)","border-right-color":"rgb(0, 0, 0)","border-bottom-color":"rgb(0, 0, 0)","border-left-color":"rgb(0, 0, 0)"},"silex-id-1439554967492-62":{"width":"77px","top":"84px","left":"278px","box-sizing":"content-box","min-height":"45px"},"silex-id-1439554967286-60":{"width":"133px","top":"84px","left":"377px","box-sizing":"content-box","min-height":"36px"},"silex-id-1439554966975-57":{"width":"133px","top":"83px","left":"529px","box-sizing":"content-box","min-height":"37px"},"silex-id-1439554966767-55":{"width":"128px","top":"83px","left":"681px","box-sizing":"content-box","min-height":"45px"},"silex-id-1439554966563-53":{"width":"95px","top":"83px","left":"829px","box-sizing":"content-box","min-height":"45px"},"silex-id-1439554966458-52":{"width":"960px","top":"-14px","left":"0px","box-sizing":"content-box","background-color":"rgb(0, 0, 0)","min-height":"483px"},"silex-id-1439554966357-51":{"width":"232px","top":"163px","left":"0px","box-sizing":"content-box","border-top-color":"rgb(255, 255, 255)","border-right-color":"rgb(255, 255, 255)","border-bottom-color":"rgb(255, 255, 255)","border-left-color":"rgb(255, 255, 255)","border-top-width":"0px","border-right-width":"3px","border-bottom-width":"0px","border-left-width":"0px","border-top-style":"solid","border-right-style":"solid","border-bottom-style":"solid","border-left-style":"solid","background-color":"rgb(102, 88, 71)","min-height":"158px"},"silex-id-1439554966255-50":{"width":"183px","top":"22px","left":"45px","box-sizing":"content-box","min-height":"118px"},"silex-id-1439554966154-49":{"width":"232px","top":"5px","left":"0px","box-sizing":"content-box","border-top-color":"rgb(255, 255, 255)","border-right-color":"rgb(255, 255, 255)","border-bottom-color":"rgb(255, 255, 255)","border-left-color":"rgb(255, 255, 255)","border-top-width":"0px","border-right-width":"3px","border-bottom-width":"0px","border-left-width":"0px","border-top-style":"solid","border-right-style":"solid","border-bottom-style":"solid","border-left-style":"solid","background-color":"rgb(255, 153, 0)","min-height":"158px"},"silex-id-1439554966050-48":{"width":"183px","top":"17px","left":"45px","box-sizing":"content-box","min-height":"104px"},"silex-id-1439554965947-47":{"width":"726px","top":"-10px","left":"232px","box-sizing":"content-box","background-image":"url('../../../../../../../libs/templates/silex-templates/ipsoom/assets/xpdPwXTASnOUXFpIPgDs_IMG_1460_edt.jpg')","background-color":"transparent","background-size":"cover","min-height":"474px"},"silex-id-1439554965843-46":{"width":"232px","top":"321px","left":"0px","box-sizing":"content-box","border-top-color":"rgb(255, 255, 255)","border-right-color":"rgb(255, 255, 255)","border-bottom-color":"rgb(255, 255, 255)","border-left-color":"rgb(255, 255, 255)","border-top-width":"0px","border-right-width":"3px","border-bottom-width":"0px","border-left-width":"0px","border-top-style":"solid","border-right-style":"solid","border-bottom-style":"solid","border-left-style":"solid","background-color":"rgb(61, 54, 45)","min-height":"158px"},"silex-id-1439554965740-45":{"width":"183px","top":"22px","left":"45px","box-sizing":"content-box","min-height":"104px"},"silex-id-1439554965638-44":{"width":"726px","top":"5px","left":"232px","box-sizing":"content-box","background-image":"url('../../../../../../../libs/templates/silex-templates/ipsoom/assets/UJO0jYLtRte4qpyA37Xu_9X6A7388.jpg')","background-color":"transparent","background-size":"cover","min-height":"474px"},"silex-id-1439554965536-43":{"width":"726px","top":"6px","left":"233px","box-sizing":"content-box","background-image":"url('../../../../../../../libs/templates/silex-templates/ipsoom/assets/8bc72ed7.jpg')","background-color":"transparent","background-size":"cover","min-height":"474px"},"silex-id-1439554965432-42":{"width":"960px","top":"-9px","left":"0px","box-sizing":"content-box","background-color":"rgb(254, 255, 253)","min-height":"309px"},"silex-id-1439554965331-41":{"width":"290px","top":"26px","left":"37px","box-sizing":"content-box","border-top-width":"0px","border-right-width":"1px","border-bottom-width":"0px","border-left-width":"0px","border-top-style":"solid","border-right-style":"solid","border-bottom-style":"solid","border-left-style":"solid","border-top-color":"rgb(102, 88, 71)","border-right-color":"rgb(102, 88, 71)","border-bottom-color":"rgb(102, 88, 71)","border-left-color":"rgb(102, 88, 71)","background-color":"transparent","min-height":"254px"},"silex-id-1439554965230-40":{"width":"266px","top":"169px","left":"3px","box-sizing":"content-box","min-height":"91px"},"silex-id-1439554965129-39":{"width":"283px","top":"-6px","left":"0px","box-sizing":"content-box","min-height":"60px"},"silex-id-1439554965028-38":{"width":"260px","top":"66px","left":"0px","box-sizing":"content-box","border-top-width":"5px","border-right-width":"5px","border-bottom-width":"5px","border-left-width":"5px","border-top-style":"solid","border-right-style":"solid","border-bottom-style":"solid","border-left-style":"solid","border-top-color":"rgb(0, 0, 0)","border-right-color":"rgb(0, 0, 0)","border-bottom-color":"rgb(0, 0, 0)","border-left-color":"rgb(0, 0, 0)","border-image-source":"initial","border-image-slice":"initial","border-image-width":"initial","border-image-outset":"initial","border-image-repeat":"initial","background-image":"url('../../../../../../../libs/templates/silex-templates/ipsoom/assets/wood.jpg')","background-color":"rgb(0, 0, 0)","background-size":"cover","min-height":"94px"},"silex-id-1439554964925-37":{"width":"290px","top":"26px","left":"345px","box-sizing":"content-box","border-top-width":"0px","border-right-width":"1px","border-bottom-width":"0px","border-left-width":"0px","border-top-style":"solid","border-right-style":"solid","border-bottom-style":"solid","border-left-style":"solid","border-top-color":"rgb(102, 88, 71)","border-right-color":"rgb(102, 88, 71)","border-bottom-color":"rgb(102, 88, 71)","border-left-color":"rgb(102, 88, 71)","background-color":"transparent","min-height":"254px"},"silex-id-1439554964822-36":{"width":"260px","top":"66px","left":"0px","box-sizing":"content-box","border-top-width":"5px","border-right-width":"5px","border-bottom-width":"5px","border-left-width":"5px","border-top-style":"solid","border-right-style":"solid","border-bottom-style":"solid","border-left-style":"solid","border-top-color":"rgb(0, 0, 0)","border-right-color":"rgb(0, 0, 0)","border-bottom-color":"rgb(0, 0, 0)","border-left-color":"rgb(0, 0, 0)","border-image-source":"initial","border-image-slice":"initial","border-image-width":"initial","border-image-outset":"initial","border-image-repeat":"initial","background-image":"url('../../../../../../../libs/templates/silex-templates/ipsoom/assets/night.jpg')","background-color":"rgb(0, 0, 0)","background-size":"cover","min-height":"94px"},"silex-id-1439554964720-35":{"width":"266px","top":"169px","left":"3px","box-sizing":"content-box","min-height":"91px"},"silex-id-1439554964619-34":{"width":"283px","top":"-6px","left":"0px","box-sizing":"content-box","min-height":"60px"},"silex-id-1439554964518-33":{"width":"290px","top":"26px","left":"656px","box-sizing":"content-box","border-top-color":"rgb(102, 88, 71)","border-right-color":"rgb(102, 88, 71)","border-bottom-color":"rgb(102, 88, 71)","border-left-color":"rgb(102, 88, 71)","background-color":"transparent","min-height":"254px"},"silex-id-1439554964416-32":{"width":"260px","top":"66px","left":"0px","box-sizing":"content-box","border-top-width":"5px","border-right-width":"5px","border-bottom-width":"5px","border-left-width":"5px","border-top-style":"solid","border-right-style":"solid","border-bottom-style":"solid","border-left-style":"solid","border-top-color":"rgb(0, 0, 0)","border-right-color":"rgb(0, 0, 0)","border-bottom-color":"rgb(0, 0, 0)","border-left-color":"rgb(0, 0, 0)","border-image-source":"initial","border-image-slice":"initial","border-image-width":"initial","border-image-outset":"initial","border-image-repeat":"initial","background-image":"url('../../../../../../../libs/templates/silex-templates/ipsoom/assets/bench.jpg')","background-color":"rgb(0, 0, 0)","background-size":"cover","min-height":"94px"},"silex-id-1439554964315-31":{"width":"266px","top":"169px","left":"3px","box-sizing":"content-box","min-height":"91px"},"silex-id-1439554964214-30":{"width":"283px","top":"-6px","left":"0px","box-sizing":"content-box","min-height":"60px"},"silex-id-1439554964112-29":{"width":"592px","top":"333px","left":"342px","box-sizing":"content-box","min-height":"111px"},"silex-id-1439554964011-28":{"width":"225px","top":"334px","left":"41px","box-sizing":"content-box","min-height":"61px"},"silex-id-1439554963909-27":{"width":"47px","top":"327px","left":"310px","box-sizing":"content-box","min-height":"68px"},"silex-id-1439554963809-26":{"width":"47px","top":"399px","left":"647px","box-sizing":"content-box","min-height":"68px"},"silex-id-1439554963707-25":{"width":"280px","top":"469px","left":"25px","box-sizing":"content-box","background-color":"transparent","min-height":"215px"},"silex-id-1439554963605-24":{"width":"276px","top":"14px","left":"14px","box-sizing":"content-box","min-height":"147px"},"silex-id-1439554963502-23":{"width":"113px","top":"166px","left":"16px","box-sizing":"content-box","background-color":"rgba(102,88,71,1)","min-height":"34px"},"silex-id-1439554963400-22":{"width":"280px","top":"469px","left":"332px","box-sizing":"content-box","background-color":"transparent","min-height":"215px"},"silex-id-1439554963298-21":{"width":"276px","top":"14px","left":"14px","box-sizing":"content-box","min-height":"147px"},"silex-id-1439554963198-20":{"width":"113px","top":"166px","left":"16px","box-sizing":"content-box","background-color":"rgb(102, 88, 71)","min-height":"34px"},"silex-id-1439554963096-19":{"width":"280px","top":"469px","left":"639px","box-sizing":"content-box","background-color":"transparent","min-height":"215px"},"silex-id-1439554962995-18":{"width":"276px","top":"14px","left":"14px","box-sizing":"content-box","min-height":"147px"},"silex-id-1439554962893-17":{"width":"113px","top":"166px","left":"16px","box-sizing":"content-box","background-color":"rgba(102,88,71,1)","min-height":"34px"},"silex-id-1439554962792-16":{"width":"600px","top":"208px","left":"180px","box-sizing":"content-box","background-color":"transparent","min-height":"50px"},"silex-id-1439554962691-15":{"width":"264px","top":"85px","left":"37px","box-sizing":"content-box","min-height":"67px"},"silex-id-1439554962589-14":{"width":"88px","top":"88px","left":"834px","min-height":"37px"},"silex-id-1439554962488-13":{"width":"40px","top":"86px","left":"771px","min-height":"40px"},"silex-id-1439554962386-12":{"width":"25px","top":"139px","left":"663px","box-sizing":"content-box","min-height":"34.5676px"},"silex-id-1439554962283-11":{"width":"240px","top":"127px","left":"698px","box-sizing":"content-box","min-height":"52px"},"silex-id-1439554962181-10":{"width":"102px","top":"136px","left":"539px","box-sizing":"content-box","min-height":"45px"},"silex-id-1439554962078-9":{"width":"133px","top":"136px","left":"400px","box-sizing":"content-box","min-height":"45px"},"silex-id-1439554961964-8":{"width":"146px","top":"136px","left":"247px","box-sizing":"content-box","min-height":"45px"},"silex-id-1439554961840-7":{"width":"134px","top":"136px","left":"107px","box-sizing":"content-box","min-height":"45px"},"silex-id-1439554961739-6":{"width":"65px","top":"136px","left":"37px","box-sizing":"content-box","min-height":"45px"},"silex-id-1439554961635-5":{"width":"817px","top":"31px","left":"2px","box-sizing":"content-box","min-height":"189px"},"silex-id-1439554961533-4":{"width":"726px","top":"321px","left":"2px","min-height":"474px"},"silex-id-1439554961432-3":{"width":"817px","top":"31px","left":"2px","box-sizing":"content-box","min-height":"189px"},"silex-id-1439554961331-2":{"width":"817px","top":"31px","left":"2px","box-sizing":"content-box","min-height":"189px"},"silex-id-1439554961229-1":{"width":"100px","top":"378px","left":"288px","background-color":"transparent","min-height":"100px"},"silex-id-1490693355800-0":{"width":"218px","min-height":"106px","top":"19px","left":"8px"},"silex-id-1490693608161-2":{"min-height":"138px","background-color":"transparent","top":"15px","left":"647px","width":"960px"},"silex-id-1490693608162-3":{"background-color":"transparent","top":"0px","left":"0px","min-width":"960px"},"silex-id-1490693798022-4":{"min-height":"474px","background-color":"transparent","top":"15px","left":"647px","width":"960px"},"silex-id-1490693798023-5":{"background-color":"transparent","top":"178px","left":"5px","min-width":"960px"},"silex-id-1490693931163-6":{"min-height":"703px","background-color":"transparent","top":"15px","left":"545px","width":"960px"},"silex-id-1490693931165-7":{"background-color":"transparent","top":"686px","left":"0px","min-width":"960px"},"silex-id-1490694042604-8":{"min-height":"269px","background-color":"transparent"},"silex-id-1490694042605-9":{"background-color":"transparent","top":"931px","left":"0px"},"silex-id-1490694152449-10":{"min-height":"236px","background-color":"transparent","top":"15px","left":"545px","width":"960px"},"silex-id-1490694152451-11":{"background-color":"transparent","top":"433px","left":"NaNpx","min-width":"960px"},"silex-id-1490694217944-12":{"min-height":"236px","background-color":"transparent"},"silex-id-1490694217944-13":{"background-color":"transparent","top":"171px","left":"0px"},"silex-id-1490694237193-14":{"min-height":"232px","background-color":"transparent","top":"15px","left":"545px","width":"960px"},"silex-id-1490694237194-15":{"background-color":"transparent","top":"171px","left":"0px","min-width":"960px"},"silex-id-1490694258062-16":{"min-height":"744px","background-color":"transparent","border-width":"","border-style":"","border-color":"#000000","top":"15px","left":"329px","width":"960px"},"silex-id-1490694258064-17":{"background-color":"transparent","top":"171px","left":"0px","border-color":"#000000","min-width":"960px"},"silex-id-1490701849668-18":{"min-height":"480px","background-color":"transparent","top":"15px","left":"545px","width":"960px"},"silex-id-1490701849669-19":{"background-color":"transparent","top":"159px","left":"0px","min-width":"960px","background-image":"url('../../../../../../../libs/templates/silex-templates/ipsoom/assets/UJO0jYLtRte4qpyA37Xu_9X6A7388.jpg')","background-size":"cover","background-position":"center center"},"silex-id-1490701905043-20":{"min-height":"480px","background-color":"transparent"},"silex-id-1490701905049-21":{"background-color":"transparent","top":"100px","left":"NaNpx","background-image":"url('../../../../../../../libs/templates/silex-templates/ipsoom/assets/nQZcA7PRTyuduZPSZQ88_wanderlust.jpg')","background-size":"cover","background-position":"center center"},"silex-id-1490701944667-22":{"min-height":"480px","background-color":"transparent"},"silex-id-1490701944668-23":{"background-color":"transparent","top":"100px","left":"NaNpx","background-image":"url('../../../../../../../libs/templates/silex-templates/ipsoom/assets/xpdPwXTASnOUXFpIPgDs_IMG_1460_edt.jpg')","background-size":"cover","background-position":"bottom center"},"silex-id-1492776401689-1":{"width":"456px","height":"587px","background-color":"transparent","top":"83px","left":"1px"},"silex-id-1492776672785-2":{"height":"571px","width":"472px","background-color":"transparent","top":"91px","left":"487px","border-width":"1px 1px 1px 1px ","border-style":"solid","border-color":"#ffffff"}},"mobile":{"silex-id-1439554965432-42":{"top":"141px","left":"11px","width":"423px","min-height":"979px"},"silex-id-1439554964011-28":{"top":"1603px","left":"11px","width":"423px","min-height":"90px"},"silex-id-1439554964112-29":{"top":"1183px","left":"57px","width":"331px","min-height":"172px"},"silex-id-1439554962283-11":{"top":"2129px","left":"1px","width":"240px","min-height":"38px"},"silex-id-1439554962691-15":{"top":"2000px","left":"13px","width":"419px","min-height":"125px"},"silex-id-1439554966357-51":{"top":"0px","left":"93px","width":"234px","min-height":"158px"},"silex-id-1439554965331-41":{"top":"32px","left":"10px","width":"402px","min-height":"262px"},"silex-id-1439554965028-38":{"top":"158px","left":"5px","width":"382px","min-height":"94px"},"silex-id-1439554965129-39":{"top":"91px","left":"10px","width":"382px","min-height":"67px"},"silex-id-1439554965230-40":{"top":"0px","left":"10px","width":"382px","min-height":"91px"},"silex-id-1439554964925-37":{"top":"359px","left":"10px","width":"402px","min-height":"262px"},"silex-id-1439554964822-36":{"top":"0px","left":"5px","width":"382px","min-height":"94px"},"silex-id-1439554964720-35":{"top":"104px","left":"10px","width":"382px","min-height":"91px"},"silex-id-1439554964619-34":{"top":"196px","left":"10px","width":"382px","min-height":"66px"},"silex-id-1439554964518-33":{"top":"685px","left":"11px","width":"414px","min-height":"262px"},"silex-id-1439554964416-32":{"top":"0px","left":"5px","width":"394px","min-height":"94px"},"silex-id-1439554964315-31":{"top":"104px","left":"10px","width":"394px","min-height":"91px"},"silex-id-1439554964214-30":{"top":"196px","left":"10px","width":"394px","min-height":"66px"},"silex-id-1439554961533-4":{"top":"797px","left":"11px","width":"423px","min-height":"307px"},"silex-id-1439554963707-25":{"top":"1241px","left":"11px","width":"423px","min-height":"215px"},"silex-id-1439554963605-24":{"top":"5px","left":"11px","width":"401px","min-height":"160px"},"silex-id-1439554963400-22":{"top":"1456px","left":"11px","width":"423px","min-height":"215px"},"silex-id-1439554963298-21":{"top":"5px","left":"11px","width":"401px","min-height":"160px"},"silex-id-1439554963096-19":{"top":"1671px","left":"11px","width":"423px","min-height":"215px"},"silex-id-1439554962995-18":{"top":"5px","left":"11px","width":"401px","min-height":"160px"}},"componentData":{"silex-id-1492776401689-1":{"name":"form1","templateName":"form","field1":false,"label1":"","label2":"","label3":"","placeholder3":"Your Message"},"silex-id-1492776672785-2":{"name":"map1","templateName":"map"}}}]
    </script>




    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=2.2" data-silex-viewport="">

















































    <script src="//editor.silex.me/static/2.7/osm/ol.js" data-dependency=""></script>


    <style id="current-page-style">
        .page-home {
            display: inherit;
        }
    </style>
    <!-- Silex HEAD tag do not remove -->
    <!-- End of Silex HEAD tag do not remove -->
</head>

<body data-silex-type="container" class="silex-id-1439554967896-66 enable-mobile gform silex-runtime" data-silex-id="silex-id-1439554967896-66">
    <div data-silex-type="container" class="prevent-draggable container-element editable-style silex-id-1490693608162-3 section-element hide-on-mobile" data-silex-id="silex-id-1490693608162-3">
        <div data-silex-type="container" class="editable-style silex-element-content website-width silex-id-1490693608161-2 silex-container-content container-element prevent-draggable" data-silex-id="silex-id-1490693608161-2">
            <div data-silex-type="text" class="editable-style text-element silex-id-1439554967492-62 nav nav-mark page-link-active" data-silex-id="silex-id-1439554967492-62" data-silex-href="#!page-home">
                <div class="silex-element-content normal">
                    <div style="text-align: center;">Home</div>
                </div>
            </div>
            <div data-silex-type="text" class="editable-style text-element silex-id-1439554967286-60 nav nav-mark" data-silex-id="silex-id-1439554967286-60" data-silex-href="#!page-our-mission">
                <div class="silex-element-content normal">
                    <div style="text-align: center;">Our mission</div>
                </div>
            </div>
            <div data-silex-type="text" class="editable-style text-element silex-id-1439554966975-57 nav nav-mark" data-silex-id="silex-id-1439554966975-57" data-silex-href="#!page-news-press">
                <div class="silex-element-content normal">
                    <div style="text-align: center;">ГОЛОВНА<br></div>
                </div>
            </div>


            <div data-silex-type="text" class="editable-style text-element silex-id-1439554966767-55 nav nav-mark" data-silex-id="silex-id-1439554966767-55" data-silex-href="#!page-how-to-help">
                <div class="silex-element-content normal">
                    <div style="text-align: center;">How to help</div>
                </div>
            </div>
            <div data-silex-type="text" class="editable-style text-element silex-id-1439554966563-53 nav nav-mark" data-silex-id="silex-id-1439554966563-53" data-silex-href="#!page-contact">
                <div class="silex-element-content normal">
                    <div style="text-align: center;">Contact</div>
                </div>
            </div>
            <div data-silex-type="image" class="editable-style silex-id-1490693355800-0 image-element page-link-active" data-silex-id="silex-id-1490693355800-0" data-silex-href="#!page-home"><img src="../../../../../../../libs/templates/silex-templates/ipsoom/assets/ipsoom-logo.png" class="silex-element-content"></div>
        </div>
    </div>
    <div data-silex-type="container" class="prevent-draggable container-element editable-style silex-id-1490693798023-5 section-element page-help-children paged-element page-join-volunteer page-home hide-on-mobile" data-silex-id="silex-id-1490693798023-5">
        <div data-silex-type="container" class="editable-style silex-element-content website-width silex-id-1490693798022-4 silex-container-content container-element prevent-draggable" data-silex-id="silex-id-1490693798022-4">
            <div data-silex-type="container" class="editable-style container-element silex-id-1439554966458-52" data-silex-id="silex-id-1439554966458-52">


















                <div data-silex-type="container" class="editable-style container-element sub-nav silex-id-1439554966357-51 hide-on-mobile" data-silex-href="#!page-join-volunteer" data-silex-id="silex-id-1439554966357-51">




                    <div data-silex-type="text" class="editable-style text-element silex-id-1439554966255-50 page-link-active" data-silex-href="#!page-home" data-silex-id="silex-id-1439554966255-50">
                        <div class="silex-element-content normal">
                            <h1 class="heading1">Cow&nbsp;</h1>
                            <p class="normal">Volunteer</p>
                        </div>
                    </div>
                </div>
                <div data-silex-type="container" class="editable-style container-element sub-nav silex-id-1439554966154-49 hide-on-mobile page-link-active" data-silex-href="#!page-home" data-silex-id="silex-id-1439554966154-49">




                    <div data-silex-type="text" class="editable-style text-element silex-id-1439554966050-48" data-silex-id="silex-id-1439554966050-48">
                        <div class="silex-element-content normal">
                            <h1 class="heading1">Lorem</h1>
                            <div>Donations</div>
                        </div>
                    </div>
                </div>




                <div data-silex-type="container" class="editable-style container-element sub-nav silex-id-1439554965843-46 hide-on-mobile" data-silex-href="#!page-help-children" data-silex-id="silex-id-1439554965843-46">




                    <div data-silex-type="text" class="editable-style text-element silex-id-1439554965740-45 page-link-active" data-silex-href="#!page-home" data-silex-id="silex-id-1439554965740-45">
                        <div class="silex-element-content normal">
                            <h1 class="heading1">Tip</h1>Children</div>
                    </div>

                </div>
                <div data-silex-type="container" class="editable-style container-element main-picture page-join-volunteer paged-element silex-id-1439554965638-44" data-silex-id="silex-id-1439554965638-44">








                </div>
                <div data-silex-type="container" class="editable-style container-element main-picture page-home paged-element silex-id-1439554965536-43" data-silex-id="silex-id-1439554965536-43">








                </div>
            </div>
            <div data-silex-type="container" class="editable-style container-element main-picture silex-id-1439554965947-47 page-help-children paged-element" data-silex-id="silex-id-1439554965947-47">








            </div>
        </div>
    </div>
    <div data-silex-type="container" class="prevent-draggable container-element editable-style silex-id-1490693931165-7 section-element page-home paged-element page-join-volunteer page-help-children" data-silex-id="silex-id-1490693931165-7">
        <div data-silex-type="container" class="editable-style silex-element-content website-width silex-id-1490693931163-6 silex-container-content container-element prevent-draggable" data-silex-id="silex-id-1490693931163-6">
            <div data-silex-type="container" class="editable-style container-element white-bg silex-id-1439554965432-42" data-silex-id="silex-id-1439554965432-42">








                <div data-silex-type="container" class="editable-style container-element silex-id-1439554965331-41" data-silex-id="silex-id-1439554965331-41">







                    <div data-silex-type="text" class="editable-style text-element silex-id-1439554965129-39" data-silex-id="silex-id-1439554965129-39">
                        <div class="silex-element-content normal">
                            <h2 class="heading2">Les casacaca</h2>
                        </div>
                    </div>
                    <div data-silex-type="container" class="editable-style container-element silex-id-1439554965028-38" data-silex-id="silex-id-1439554965028-38">
                    </div>
                    <div data-silex-type="text" class="editable-style text-element silex-id-1439554965230-40" data-silex-id="silex-id-1439554965230-40">
                        <div class="silex-element-content normal">
                            <p class="normal">Cow prosciutto fatback ball tip bacon hamburger nostrud tail fugiat cupidatat frankfurter
                            </p>
                        </div>
                    </div>
                </div>
                <div data-silex-type="container" class="editable-style container-element silex-id-1439554964925-37" data-silex-id="silex-id-1439554964925-37">
                    <div data-silex-type="text" class="editable-style text-element silex-id-1439554964619-34" data-silex-id="silex-id-1439554964619-34">
                        <div class="silex-element-content normal">
                            <h2 class="heading2">Joe Lie</h2>
                        </div>
                    </div>




                    <div data-silex-type="container" class="editable-style container-element silex-id-1439554964822-36" data-silex-id="silex-id-1439554964822-36">
                    </div>

                    <div data-silex-type="text" class="editable-style text-element silex-id-1439554964720-35" data-silex-id="silex-id-1439554964720-35">
                        <div class="silex-element-content normal">
                            <p class="normal"></p>
                            <p class="normal">Et ullamco officia nostrud, short ribs sunt commodo. Porchetta officia pork chop laborum, do cupim hamburger lorem.&nbsp;
                            </p>
                            <p class="normal"></p>
                        </div>
                    </div>

                </div>
                <div data-silex-type="container" class="editable-style container-element silex-id-1439554964518-33" data-silex-id="silex-id-1439554964518-33">
                    <div data-silex-type="text" class="editable-style text-element silex-id-1439554964214-30" data-silex-id="silex-id-1439554964214-30">
                        <div class="silex-element-content normal">
                            <h2 class="heading2">Pisica Wow</h2>
                        </div>
                    </div>




                    <div data-silex-type="container" class="editable-style container-element silex-id-1439554964416-32" data-silex-id="silex-id-1439554964416-32">
                    </div>

                    <div data-silex-type="text" class="editable-style text-element silex-id-1439554964315-31" data-silex-id="silex-id-1439554964315-31">
                        <div class="silex-element-content normal">
                            <p class="normal">Beef ribs reprehenderit non shankle shank capicola, ea labore picanha. Short loin ham nulla, dolore</p>
                        </div>
                    </div>

                </div>
            </div>
            <div data-silex-type="text" class="editable-style text-element silex-id-1439554964011-28 page-link-active" data-silex-href="#!page-home" data-silex-id="silex-id-1439554964011-28">
                <div class="silex-element-content normal">
                    <h1 class="heading1">Our Mission</h1>
                    <h1 class="heading1"></h1>
                </div>
            </div>
            <div data-silex-type="text" class="editable-style text-element silex-id-1439554963909-27" data-silex-id="silex-id-1439554963909-27">
                <div class="silex-element-content normal">
                    <div>
                        <font size="7"><br></font>
                    </div>
                    <font size="7">“</font>
                </div>
            </div>
            <div data-silex-type="text" class="editable-style text-element silex-id-1439554964112-29" data-silex-id="silex-id-1439554964112-29">
                <div class="silex-element-content normal">
                    <p class="normal"><i></i>
                    </p>
                    <p class="normal"><i>Salami
 do
 in
 est, chuck
 reprehenderit
 irure
 porchetta
 cillum.  Nisi
 short loin
 ball tip
 rump
 shoulder, ribeye
 turducken
 tri-tip
 pancetta
 salami
 nulla
 porchetta
 ground round
 laboris
 id.  Hamburger
 exercitation
 frankfurter, eiusmod
 nostrud
 cow
 ham
 drumstick
 strip steak
 minim
 picanha
 quis.&nbsp;</i>
                    </p>
                    <p class="normal"></p>
                </div>
            </div>
            <div data-silex-type="text" class="editable-style text-element silex-id-1439554963809-26" data-silex-id="silex-id-1439554963809-26">
                <div class="silex-element-content normal">
                    <div>
                        <font size="7"><br></font>
                    </div>
                    <font size="7">”</font>
                </div>
            </div>
            <div data-silex-type="container" class="editable-style container-element silex-id-1439554963707-25" data-silex-id="silex-id-1439554963707-25">


                <div data-silex-type="text" class="editable-style text-element silex-id-1439554963605-24" data-silex-id="silex-id-1439554963605-24">
                    <div class="silex-element-content normal">
                        <h1 class="heading1">June
                            <font color="#ff9900">13</font>
                            <font color="#999999">2014</font>
                        </h1>
                        <div>
                            <font color="#999999">
                                <p class="normal">Salami do in est.&nbsp;
                                </p>
                                <p class="normal">Nisi short loin ball tip rump shoulder, ribeye turducken tri-tip pancetta.
                                </p>
                            </font>
                        </div>
                        <h1 class="heading1"></h1>
                    </div>
                </div>



                <div data-silex-type="text" class="editable-style text-element button-read-more silex-id-1439554963502-23 page-link-active" data-silex-href="#!page-home" data-silex-id="silex-id-1439554963502-23">
                    <div class="silex-element-content normal">
                        <div style="text-align: center;">READ MORE</div>
                    </div>
                </div>
            </div>
            <div data-silex-type="container" class="editable-style container-element silex-id-1439554963400-22" data-silex-id="silex-id-1439554963400-22">


                <div data-silex-type="text" class="editable-style text-element silex-id-1439554963298-21" data-silex-id="silex-id-1439554963298-21">
                    <div class="silex-element-content normal">
                        <h1 class="heading1">June
                            <font color="#ff9900">13</font>
                            <font color="#999999">2014</font>
                        </h1>
                        <div>
                            <font color="#999999">
                                <p class="normal">Salami do in est.&nbsp;
                                </p>
                                <p class="normal">Nisi short loin ball tip rump shoulder, ribeye turducken tri-tip pancetta.
                                </p>
                            </font>
                        </div>
                        <h1 class="heading1"></h1>
                    </div>
                </div>



                <div data-silex-type="text" class="editable-style text-element button-read-more silex-id-1439554963198-20" data-silex-href="#!page-join-volunteer" data-silex-id="silex-id-1439554963198-20">
                    <div class="silex-element-content normal">
                        <div style="text-align: center;">READ MORE</div>
                    </div>
                </div>
            </div>
            <div data-silex-type="container" class="editable-style container-element silex-id-1439554963096-19" data-silex-id="silex-id-1439554963096-19">


                <div data-silex-type="text" class="editable-style text-element silex-id-1439554962995-18" data-silex-id="silex-id-1439554962995-18">
                    <div class="silex-element-content normal">
                        <h1 class="heading1">June
                            <font color="#ff9900">13</font>
                            <font color="#999999">2014</font>
                        </h1>
                        <div>
                            <font color="#999999">
                                <p class="normal">Salami do in est.&nbsp;
                                </p>
                                <p class="normal">Nisi short loin ball tip rump shoulder, ribeye turducken tri-tip pancetta.
                                </p>
                            </font>
                        </div>
                        <h1 class="heading1"></h1>
                    </div>
                </div>



                <div data-silex-type="text" class="editable-style text-element button-read-more silex-id-1439554962893-17" data-silex-href="#!page-help-children" data-silex-id="silex-id-1439554962893-17">
                    <div class="silex-element-content normal">
                        <div style="text-align: center;">READ MORE</div>
                    </div>
                </div>
            </div>







        </div>
    </div>











    <div class=""></div>




























    <div class="silex-pages">
        <div data-silex-type="image" data-silex-id="silex-id-hamburger-menu" class="menu-button editable-style silex-id-hamburger-menu image-element page-page-1 paged-element prevent-draggable prevent-resizable"><img alt="open mobile menu" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADIAAAAoCAYAAAC8cqlMAAAB5UlEQVR42u2ZPWvCUBSGM+UfFO3e3dLu/QN+oKj4EUXRQREEJYgoiCAu6qCogyDo7iJ21UUaKqEgCC4iiEMGB3UVgsnpTWj/wfVK2nvhGbKEPJyT996TMMzPGg6H5mKx+GgkyuWyeTQasb8OTDwef4tEIp8+n+/LYIjJZJJHQiwzm81M6OLDarWqNpsNjEYgEJCy2ewT0+/3TagighElNFAnQT6ft1ARKkJFqMgfFvF4PFpuEwFtdrcRqVarIIoirFYrIiyXSxiPx+B2u/GJBINBuF6vQHopigK1Wg2fCMdxcLlciIuoqgqNRgOfiN1uB3Qwg91uB8fjkQiHwwEmkwne1qLxS0VuKKJle71eh06nQ4Rmswk8z+MVcTqdsNlsQJZlotF7Pp8hk8ngE4lGo/qN7xG/vV4Pb0Xm8zlxkdPpBGgMx/+yJxIJKBQKRMjlcuBwOGhq/Q+RcDgMsViMCFrAuFwu/CKDwQC22y1IkkSE/X4PgiDo+xc2Ea0S9zjGa/Hb7Xbxifj9fj0K7yFSqVTwtlY6nYbpdKpPiSRYLBbQarX0PYymFhWhIlSEilCRW6GdyUqlkoVZr9dsKpXiOY6TtW+7BkNBz/7ebrcf9L+6Xq+XRYPMMyrTq5EIhUIvaAjTJb4BBNQ2yhnth0wAAAAASUVORK5CYII="
                class="silex-element-content"></div><a id="page-home" data-silex-type="page" class="page-element page-link-active">Home</a><a id="page-join-volunteer" data-silex-type="page" class="page-element">Join Volunteer</a><a id="page-help-children"
            data-silex-type="page" class="page-element">Help Children</a><a id="page-our-mission" data-silex-type="page" class="page-element">Our Mission</a><a id="page-news-press" data-silex-type="page" class="page-element">News &amp; Press</a><a id="page-how-to-help"
            data-silex-type="page" class="page-element">How to Help</a><a id="page-contact" data-silex-type="page" class="page-element">Contact</a></div>






































    <div data-silex-type="container" class="prevent-draggable container-element editable-style silex-id-1490694258064-17 section-element page-contact paged-element" data-silex-id="silex-id-1490694258064-17">
        <div data-silex-type="container" class="editable-style silex-element-content website-width silex-id-1490694258062-16 silex-container-content container-element prevent-draggable" data-silex-id="silex-id-1490694258062-16">

            <div data-silex-type="html" class="editable-style silex-id-1492776401689-1 html-element silex-component silex-component-form silex-use-height-not-minheight" data-silex-id="silex-id-1492776401689-1">
                <div class="silex-element-content">
                    <form id="id_1492776633023_506" action="https://formspree.io/your@email.com" method="POST">


                        <div>

                            <input required="" id="field2" name="field2" placeholder="your@email.com" type="text">
                        </div>


                        <div>

                            <textarea required="" id="field3" name="field3" placeholder="Your Message"></textarea>
                        </div>

                        <input value="Send" type="submit">
                    </form>
                    <style>
                        #id_1492776633023_506 input[type=text],
                        select {
                            width: 100%;
                            padding: 12px 20px;
                            margin: 8px 0;
                            display: inline-block;
                            border: 1px solid #ccc;
                            border-radius: 3px;
                            box-sizing: border-box;
                        }
                        
                        #id_1492776633023_506 input[type=submit] {
                            width: 100%;
                            background-color: #4CAF50;
                            color: #FFFFFF;
                            padding: 14px 20px;
                            margin: 8px 0;
                            border: 1px solid #4CAF50;
                            border-radius: 3px;
                            cursor: pointer;
                        }
                        
                        #id_1492776633023_506 textarea {
                            width: 100%;
                            height: 150px;
                            padding: 12px 20px;
                            box-sizing: border-box;
                            border: 2px solid #ccc;
                            border-radius: 3px;
                            background-color: #f8f8f8;
                            font-size: 16px;
                            resize: none;
                        }
                        
                        #id_1492776633023_506 label {
                            color: #000000;
                        }
                        
                        #id_1492776633023_506 {
                            border-radius: 3px;
                            display: flex;
                            flex-direction: column;
                            justify-content: space-between;
                            height: 100%;
                        }
                    </style>

                </div>
            </div>
            <div data-silex-type="html" class="editable-style silex-id-1492776672785-2 html-element silex-component silex-component-map silex-use-height-not-minheight" data-silex-id="silex-id-1492776672785-2">
                <div class="silex-element-content">
                    <div id="mapdiv_1492776672835_337">
                        <div class="ol-viewport" style="position: relative; overflow: hidden; width: 100%; height: 100%; touch-action: none;" data-view="28"><canvas style="width: 100%; height: 100%; display: none;" class="ol-unselectable"></canvas>
                            <div class="ol-overlaycontainer"></div>
                            <div class="ol-overlaycontainer-stopevent">
                                <div class="ol-zoom ol-unselectable ol-control"><button class="ol-zoom-in" type="button" title="Zoom in">+</button><button class="ol-zoom-out" type="button" title="Zoom out">−</button></div>
                                <div class="ol-rotate ol-unselectable ol-control ol-hidden"><button class="ol-rotate-reset" type="button" title="Reset rotation"><span class="ol-compass">⇧</span></button></div>
                                <div class="ol-attribution ol-unselectable ol-control ol-collapsed" style="display: none;">
                                    <ul>
                                        <li style="display: none;"></li>
                                    </ul><button type="button" title="Attributions"><span>i</span></button></div>
                            </div>
                        </div>
                    </div>
                    <style>
                        #mapdiv_1492776672835_337 {
                            width: 100%;
                            height: 100%;
                        }
                    </style>
                    <script>
                        function init_1492776672835_337() {
                            if(!$('body').hasClass('silex-runtime') && typeof(ol) === 'undefined') {
                                // wait for dependencies to be loaded
                                setTimeout(init_1492776672835_337, 100);
                                return;
                            }
                        
                            // apply position and zoom
                            // from map URL //www.openstreetmap.org/#map=18/48.88680/2.34235&layers=C
                            var params = '//www.openstreetmap.org/#map=18/48.87378/2.29489&layers=C'.match(/.*map=([0-9]*)\/(.*)\/(.*)&layers=(.)/);
                            if(params) {
                                var zoom = parseFloat(params[1]);
                                var lat = parseFloat(params[2]);
                                var lon = parseFloat(params[3]);
                                var layer = params[4];
                                var center = ol.proj.fromLonLat([lon, lat]);
                                var map = new ol.Map({
                                  layers: [
                                    new ol.layer.Tile({
                                      source: new ol.source.OSM()
                                    })
                                  ],
                                  target: 'mapdiv_1492776672835_337',
                                  view: new ol.View({
                                    center: center,
                                    zoom: zoom
                                  })
                                });
                                
                                var iconFeature = new ol.Feature({
                                    geometry: new ol.geom.Point(center)
                                });
                                var vectorSource = new ol.source.Vector({
                                    features: [iconFeature]
                                });
                                var vectorLayer = new ol.layer.Vector({
                                    source: vectorSource
                                });
                                var iconStyle = new ol.style.Style({
                                    image: new ol.style.Icon(({
                                        anchor: [0.5, 1],
                                        anchorXUnits: 'fraction',
                                        anchorYUnits: 'fraction',
                                        opacity: 1,
                                        src: 'https://openlayers.org/en/v4.0.1/examples/data/icon.png'
                                    }))
                                });
                                iconFeature.setStyle(iconStyle);
                                map.addLayer(vectorLayer);
                                
                            }
                        }
                        init_1492776672835_337();
                        $(document).on('silex:resize', function() {
                            $('#mapdiv_1492776672835_337').empty();
                            init_1492776672835_337();
                        });
                    </script>
                </div>
            </div>
        </div>
    </div>




    <div data-silex-type="container" class="prevent-draggable container-element editable-style silex-id-1490694152451-11 section-element page-our-mission paged-element" data-silex-id="silex-id-1490694152451-11">
        <div data-silex-type="container" class="editable-style silex-element-content website-width silex-id-1490694152449-10 silex-container-content container-element prevent-draggable" data-silex-id="silex-id-1490694152449-10">
            <div data-silex-type="text" class="editable-style text-element silex-id-1439554961635-5" data-silex-id="silex-id-1439554961635-5">
                <div class="silex-element-content normal">
                    <h1 class="heading1">Our Mission</h1>
                    <p class="normal">Salami do in est, chuck reprehenderit irure porchetta cillum. Nisi short loin ball tip rump shoulder, ribeye turducken tri-tip pancetta salami nulla porchetta ground round laboris id. Hamburger exercitation frankfurter, eiusmod nostrud
                        cow ham drumstick strip steak minim picanha quis. Beef ex turkey eu nostrud meatball laboris.
                    </p>
                </div>
            </div>
        </div>
    </div>
    <div data-silex-type="container" class="prevent-draggable container-element editable-style silex-id-1490701849669-19 section-element page-our-mission paged-element" data-silex-id="silex-id-1490701849669-19">
        <div data-silex-type="container" class="editable-style silex-element-content website-width silex-id-1490701849668-18 silex-container-content container-element prevent-draggable" data-silex-id="silex-id-1490701849668-18"></div>
    </div>

    <div data-silex-type="container" class="prevent-draggable container-element editable-style silex-id-1490694217944-13 section-element page-news-press paged-element" data-silex-id="silex-id-1490694217944-13">
        <div data-silex-type="container" class="editable-style silex-element-content website-width silex-id-1490694217944-12 silex-container-content container-element prevent-draggable" data-silex-id="silex-id-1490694217944-12">
            <div data-silex-type="text" class="editable-style text-element silex-id-1439554961432-3" data-silex-id="silex-id-1439554961432-3">
                <div class="silex-element-content normal">
                    <h1 class="heading1">News and Press</h1>
                    <p class="normal">Salami do in est, chuck reprehenderit irure porchetta cillum. Nisi short loin ball tip rump shoulder, ribeye turducken tri-tip pancetta salami nulla porchetta ground round laboris id. Hamburger exercitation frankfurter, eiusmod nostrud
                        cow ham drumstick strip steak minim picanha quis. Beef ex turkey eu nostrud meatball laboris.
                    </p>
                </div>
            </div>
        </div>
    </div>
    <div data-silex-type="container" class="prevent-draggable container-element editable-style silex-id-1490701905049-21 section-element page-news-press paged-element" data-silex-id="silex-id-1490701905049-21">
        <div data-silex-type="container" class="editable-style silex-element-content website-width silex-id-1490701905043-20 silex-container-content container-element prevent-draggable" data-silex-id="silex-id-1490701905043-20"></div>
    </div>

    <div data-silex-type="container" class="prevent-draggable container-element editable-style silex-id-1490694237194-15 section-element page-how-to-help paged-element" data-silex-id="silex-id-1490694237194-15">
        <div data-silex-type="container" class="editable-style silex-element-content website-width silex-id-1490694237193-14 silex-container-content container-element prevent-draggable" data-silex-id="silex-id-1490694237193-14">
            <div data-silex-type="text" class="editable-style text-element silex-id-1439554961331-2" data-silex-id="silex-id-1439554961331-2">
                <div class="silex-element-content normal">
                    <h1 class="heading1">How to Help</h1>
                    <p class="normal">Salami do in est, chuck reprehenderit irure porchetta cillum. Nisi short loin ball tip rump shoulder, ribeye turducken tri-tip pancetta salami nulla porchetta ground round laboris id. Hamburger exercitation frankfurter, eiusmod nostrud
                        cow ham drumstick strip steak minim picanha quis. Beef ex turkey eu nostrud meatball laboris.
                    </p>
                </div>
            </div>
        </div>
    </div>
    <div data-silex-type="container" class="prevent-draggable container-element editable-style silex-id-1490701944668-23 section-element page-how-to-help paged-element" data-silex-id="silex-id-1490701944668-23">
        <div data-silex-type="container" class="editable-style silex-element-content website-width silex-id-1490701944667-22 silex-container-content container-element prevent-draggable" data-silex-id="silex-id-1490701944667-22"></div>
    </div>
    <div data-silex-type="container" class="prevent-draggable container-element editable-style silex-id-1490694042605-9 section-element" data-silex-id="silex-id-1490694042605-9">
        <div data-silex-type="container" class="editable-style silex-element-content website-width silex-id-1490694042604-8 silex-container-content container-element prevent-draggable" data-silex-id="silex-id-1490694042604-8">
            <div data-silex-type="image" class="editable-style image-element silex-id-1439554962589-14" data-silex-href="https://twitter.com/silexlabs" data-silex-id="silex-id-1439554962589-14"><img src="../../../../../../../libs/templates/silex-templates/ipsoom/assets/sprite_social.png" class="silex-element-content">
            </div>
            <div data-silex-type="text" class="editable-style text-element logo silex-id-1439554962691-15 page-link-active" data-silex-href="#!page-home" data-silex-id="silex-id-1439554962691-15">
                <div class="silex-element-content normal">
                    <header class="title">
                        <font size="6">Ipsoom&nbsp;<span style="color: rgb(254, 255, 253);">Center</span></font>
                    </header>
                </div>
            </div>
            <div data-silex-type="image" class="editable-style image-element silex-id-1439554962488-13" data-silex-href="//github.com/silexlabs/" data-silex-id="silex-id-1439554962488-13"><img src="../../../../../../../libs/templates/silex-templates/ipsoom/assets/github@2x.png" class="silex-element-content">
            </div>
            <div data-silex-type="image" class="editable-style image-element silex-id-1439554962386-12" data-silex-id="silex-id-1439554962386-12"><img src="../../../../../../../libs/templates/silex-templates/ipsoom/assets/form_icon_phone.png" class="silex-element-content">
            </div>
            <div data-silex-type="text" class="editable-style text-element silex-id-1439554962283-11" data-silex-id="silex-id-1439554962283-11">
                <div class="silex-element-content normal">
                    <font size="6"><br>+1 800
                        <font color="#999999">990722</font>
                    </font>
                </div>
            </div>
            <div data-silex-type="text" class="editable-style text-element silex-id-1439554962181-10 nav hide-on-mobile nav-mark" data-silex-href="#!page-contact" data-silex-id="silex-id-1439554962181-10">
                <div class="silex-element-content normal">
                    <div style="text-align: center;">Contact</div>
                </div>
            </div>
            <div data-silex-type="text" class="editable-style text-element silex-id-1439554962078-9 nav hide-on-mobile nav-mark" data-silex-href="#!page-how-to-help" data-silex-id="silex-id-1439554962078-9">
                <div class="silex-element-content normal">
                    <div style="text-align: center;">How to help</div>
                </div>
            </div>
            <div data-silex-type="text" class="editable-style text-element silex-id-1439554961964-8 nav hide-on-mobile nav-mark" data-silex-href="#!page-news-press" data-silex-id="silex-id-1439554961964-8">
                <div class="silex-element-content normal">
                    <div style="text-align: center;">News &amp; Press</div>
                </div>
            </div>
            <div data-silex-type="text" class="editable-style text-element silex-id-1439554961840-7 nav hide-on-mobile nav-mark" data-silex-href="#!page-our-mission" data-silex-id="silex-id-1439554961840-7">
                <div class="silex-element-content normal">
                    <div style="text-align: center;">Our mission</div>
                </div>
            </div>
            <div data-silex-type="text" class="editable-style text-element silex-id-1439554961739-6 nav hide-on-mobile nav-mark page-link-active" data-silex-href="#!page-home" data-silex-id="silex-id-1439554961739-6">
                <div class="silex-element-content normal">
                    <div style="text-align: center;">Home</div>
                </div>
            </div>
            <div data-silex-type="text" class="editable-style text-element silex-id-1439554962792-16" data-silex-id="silex-id-1439554962792-16">
                <div class="silex-element-content normal">
                    <div style="text-align: center;">Creative commons template - <span id="goog_632856061"></span><a href="//www.silex.me">powered by Silex</a><span id="goog_632856062"></span>
                    </div>
                    <div style="text-align: center;"><a href="//www.colorcombos.com/color-schemes/253/ColorCombo253.html">Color palete</a><span style="color: rgb(255, 255, 255);"> - </span><a href="//blog.templatemonster.com/2011/07/18/free-website-template-charity-jquery-slider-typography/">inspiration</a>
                        <span style="color: rgb(255, 255, 255);"> - </span><a href="https://unsplash.com/">pictures</a>
                    </div>
                    <div>
                        <br>
                    </div>
                </div>
            </div>
        </div>
    </div>




















</body>

</html>