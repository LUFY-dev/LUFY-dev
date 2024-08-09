-<!DOCTYPE html>
<html lang="en">

<head>
    <title>Morocco BLS Spain Visa: Welcome to the Official Website Spain Visa Application Centre in Morocco</title>

    <!-- Meta Tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta name="description" content="Morocco BLS Spain Visa">

    <script>

        const storedTheme = localStorage.getItem('theme')

        const getPreferredTheme = () => {
            if (storedTheme) {
                return storedTheme
            }
            return window.matchMedia('(prefers-color-scheme: dark)').matches ? 'dark' : 'light'
        }

        const setTheme = function (theme) {
            if (theme === 'auto' && window.matchMedia('(prefers-color-scheme: dark)').matches) {
                document.documentElement.setAttribute('data-bs-theme', 'dark')
            } else {
                document.documentElement.setAttribute('data-bs-theme', theme)
            }
        }

        setTheme(getPreferredTheme())

        window.addEventListener('DOMContentLoaded', () => {
            var el = document.querySelector('.theme-icon-active');
            if (el != 'undefined' && el != null) {
                const showActiveTheme = theme => {
                    const activeThemeIcon = document.querySelector('.theme-icon-active use')
                    const btnToActive = document.querySelector(`[data-bs-theme-value="${theme}"]`)
                    const svgOfActiveBtn = btnToActive.querySelector('.mode-switch use').getAttribute('href')

                    document.querySelectorAll('[data-bs-theme-value]').forEach(element => {
                        element.classList.remove('active')
                    })

                    btnToActive.classList.add('active')
                    activeThemeIcon.setAttribute('href', svgOfActiveBtn)
                }

                window.matchMedia('(prefers-color-scheme: dark)').addEventListener('change', () => {
                    if (storedTheme !== 'light' || storedTheme !== 'dark') {
                        setTheme(getPreferredTheme())
                    }
                })

                showActiveTheme(getPreferredTheme())

                document.querySelectorAll('[data-bs-theme-value]')
                    .forEach(toggle => {
                        toggle.addEventListener('click', () => {
                            const theme = toggle.getAttribute('data-bs-theme-value')
                            localStorage.setItem('theme', theme)
                            setTheme(theme)
                            showActiveTheme(theme)
                        })
                    })

            }
        })

    </script>

    <!-- Favicon -->
    <link rel="shortcut icon" href="/assets/images/favicon.png">

    <!-- Google Font -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;700&family=Poppins:wght@400;500;700&display=swap">

    <!-- Plugins CSS -->
    <link rel="stylesheet" type="text/css" href="/assets/vendor/font-awesome/css/all.min.css?v=AbA177XfpSnFEvgpYu1jMygiLabzPCJCRIBtR5jGc0k">
    <link rel="stylesheet" type="text/css" href="/assets/vendor/bootstrap-icons/bootstrap-icons.css?v=4RctOgogjPAdwGbwq-rxfwAmSpZhWaafcZR9btzUk18">
    <link rel="stylesheet" type="text/css" href="/assets/vendor/tiny-slider/tiny-slider.css?v=1CXVlacnwYLmg9X2AhCKvYcSgR53GWiU3z4qZJDrb68">
    <link rel="stylesheet" type="text/css" href="/assets/vendor/glightbox/css/glightbox.css?v=yMoCTayb6wccTz561YN_R0qkP756JifYXnA40MUtR-k">
    <link rel="stylesheet" type="text/css" href="/assets/vendor/flatpickr/css/flatpickr.min.css?v=RXPAyxHVyMLxb0TYCM2OW5R4GWkcDe02jdYgyZp41OU">
    <link rel="stylesheet" type="text/css" href="/assets/vendor/choices/css/choices.min.css?v=IhTRSpOAAOl37YqrDOlNjxD6S4lzZ_n2WqKtc03i0mE">

    <!-- Theme CSS -->
    <link rel="stylesheet" type="text/css" href="/assets/vendor/bootstrap/dist/css/bootstrap.min.css?v=YLGeXaapI0_5IgZopewRJcFXomhRMlYYjugPLSyNjTY">
    <link rel="stylesheet" type="text/css" href="/assets/css/style.css?v=de-9WIa9z8cZXAVKAywSh1vOyouay5jH6hy6oE4R0xc">

    <link rel="stylesheet" type="text/css" href="/assets/css/color.css?v=biNDUrJj74VlRbGB7tvoVV8aOPeiVsRt7L_VDdhggXQ" />

    <link rel="stylesheet" type="text/css" href="/css/site.css?v=nyttlx8tVS_Y-Y8W6R_0h9a60aa5OepPeqVafkXiVDg" />

    
    <link rel="stylesheet" type="text/css" href="/assets/vendor/kendo/css/kendo.common.min.css">
    <link rel="stylesheet" type="text/css" href="/assets/vendor/kendo/css/kendo.silver.min.css">

    <style>
    </style>
    <script src="/assets/vendor/jquery/dist/jquery.min.js"></script>
    <script src="/assets/vendor/jquery-validation/dist/jquery.validate.min.js"></script>
    <script src="/assets/vendor/jquery-ajax-unobtrusive/jquery-ajax-unobtrusive.js"></script>
    <script src="/assets/vendor/jquery-validation-unobtrusive/jquery.validate.unobtrusive.min.js"></script>
    <script type="text/javascript" src="https://5f2749aa43d4.eu-central-1.sdk.awswaf.com/5f2749aa43d4/4bc7b7b893fe/challenge.js"  defer></script>
    <script>
        $.ajaxSetup({
            beforeSend: function (xhr, options) {
                if (options.type.toUpperCase() == "POST") {
                    xhr.setRequestHeader("RequestVerificationToken", $('input:hidden[name="__RequestVerificationToken"]').val());
                }

            }
        });
    </script>
</head>
<body>
    <div class="preloader">
        <div class="preloader-item">
            <div class="spinner-grow text-primary"></div>
        </div>
    </div>
    <div id="global-overlay" class="global-overlay">
        <div class="global-overlay-loader">
        </div>
    </div>
    <header class="navbar-light header-sticky">
        <!-- Nav START -->
        <nav class="navbar navbar-expand-xl z-index-9 navbar-divider">
            <div class="container">
                <!-- Logo START -->
                <a class="navbar-brand" href="/MAR/home/index">
                    <img class="light-mode-item navbar-brand-item" src="/assets/images/logo.png" alt="BLS Logo" title="BLS Logo">
                    <img class="dark-mode-item navbar-brand-item" src="/assets/images/logo.png" alt="logo">
                </a>
                <!-- Logo END -->
                <!-- Responsive navbar toggler -->
                <button class="navbar-toggler ms-auto" type="button" data-bs-toggle="collapse" data-bs-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
                    <i class="bi bi-search fs-4"> </i>
                </button>

                <!-- Responsive navbar toggler -->
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarCollapse2" aria-controls="navbarCollapse2" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-animation">
                        <span></span>
                        <span></span>
                        <span></span>
                    </span>
                </button>

                <!-- Main navbar START -->
                <div class="navbar-collapse collapse" id="navbarCollapse">
                    <div class="col-md-9">
                        <div class="nav my-3 my-xl-0 px-4 flex-nowrap align-items-center">
                            <div class="nav-item w-100">
                                <div class="align-items-center position-relative">
                                    <div class="align-items-center text-primary" style="font-size:30px;font-weight:700;">Apply for VISA to Spain In Morocco</div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-3">
                        <div class="align-items-center position-relative">
                            <small class="text-secondary mb-1">Follow us on</small>
                            <ul class="list-inline mb-3 mt-0">
                                <li class="list-inline-item"> <a class="btn btn-sm px-2 bg-facebook mb-0" href="https://www.facebook.com/blsinternationalservices/" target="_blank" rel="noopener noreferrer"><i class="fab fa-fw fa-facebook-f"></i></a> </li>
                                <li class="list-inline-item"> <a class="btn btn-sm shadow px-2 bg-instagram mb-0" href="https://www.instagram.com/blsinternationalservicesltd/" target="_blank" rel="noopener noreferrer"><i class="fab fa-fw fa-instagram"></i></a> </li>
                                <li class="list-inline-item"> <a class="btn btn-sm shadow px-2 bg-twitter mb-0" href="https://twitter.com/blsintlservices" target="_blank" rel="noopener noreferrer"><i class="fab fa-fw fa-twitter"></i></a> </li>
                                <li class="list-inline-item"> <a class="btn btn-sm shadow px-2 bg-linkedin mb-0" href="https://www.linkedin.com/company/bls-international-services-ltd/?originalSubdomain=in" target="_blank" rel="noopener noreferrer"><i class="fab fa-fw fa-linkedin-in"></i></a> </li>
                            </ul>
                        </div>
                    </div>
                </div>

                <!-- Main navbar END -->
                <!-- Profile and notification START -->
                <ul class="nav flex-row align-items-center list-unstyled ms-xl-auto">
                    <li class="dropdown nav-item">
                        <a class="nav-link small pb-2" href="#" role="button" id="languageDropdown" data-bs-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                            <img class="w-30px me-2" src="/assets/images/flags/en-US.svg" alt=""><small>English</small>
                        </a>
                        <ul class="dropdown-menu dropdown-animation dropdown-menu-end min-w-auto" aria-labelledby="languageDropdown">
                            <li> <a class="dropdown-item me-4" href="javascript:OnLanguageChange('en-US');"><img class="fa-fw me-2" src="/assets/images/flags/en-US.svg" alt="">English</a> </li>
                            <li> <a class="dropdown-item me-4" href="javascript:OnLanguageChange('es-ES');"><img class="fa-fw me-2" src="/assets/images/flags/es-ES.svg" alt="">Español</a> </li>
                            <li> <a class="dropdown-item me-4" href="javascript:OnLanguageChange('fr-FR');"><img class="fa-fw me-2" src="/assets/images/flags/fr-FR.svg" alt="">Français</a> </li>
                        </ul>
                    </li>
                        <li class="nav-item ms-3 dropdown">
                            <!-- Avatar -->
                            <a class="avatar avatar-sm p-0 mt-0" href="#" id="profileDropdown" role="button" data-bs-auto-close="outside" data-bs-display="static" data-bs-toggle="dropdown" aria-expanded="false">
                                    <img onerror="OnPhotoError(this);" class="avatar-img rounded-2" src="/assets/images/avatar/01.jpg" alt="Profile">
                            </a>

                            <!-- Profile dropdown START -->
                            <ul class="dropdown-menu dropdown-animation dropdown-menu-end shadow pt-3" aria-labelledby="profileDropdown">
                                <!-- Profile info -->
                                <li class="px-3 mb-3">
                                    <div class="d-flex align-items-center">
                                        <!-- Avatar -->
                                        <div class="avatar me-3">
                                                <img onerror="OnPhotoError(this);" class="avatar-img rounded-circle shadow" src="/assets/images/avatar/01.jpg" alt="Profile">

                                        </div>
                                        <div>
                                            <a class="h6 mt-2 mt-sm-0" href="#">ahmed ahmed</a>
                                            <p class="small m-0">dfsdifft@gmail.com</p>
                                        </div>
                                    </div>
                                </li>

                                <!-- Links -->
                                <li> <hr class="dropdown-divider"></li>
                                <li></li>
                                <li><a class="dropdown-item" href="/MAR/account/DeleteUser"><i class="fa fa-trash fa-fw me-2"></i>Delete Account</a></li>
                                <li><a class="dropdown-item" href="/MAR/account/ChangePassword"><i class="fa fa-key fa-fw me-2"></i>Change Password</a></li>
                                <li><a class="dropdown-item bg-danger-soft-hover" href="javascript:OnLogout();"><i class="fa fa-power-off me-2"></i>Logout</a></li>
                                <li> <hr class="dropdown-divider"></li>

                                <!-- Dark mode options START -->
                                <!-- Dark mode options END-->
                            </ul>
                            <!-- Profile dropdown END -->
                        </li>
                    <!-- Profile dropdown START -->
                    <!-- Profile dropdown END -->
                </ul>
                <!-- Profile and notification END -->
            </div>
        </nav>
        <!-- Nav END -->
        <!--Main menu link START -->
        <nav class="navbar navbar-expand-xl navbar-divider">
            <div class="container px-0">
                <!-- Main navbar START -->
                <div class="navbar-collapse w-100 collapse" id="navbarCollapse2">
                    <ul class="navbar-nav nav-active-line navbar-nav-scroll">
                        <li class="nav-item"> <a class="nav-link home-active" href="https://blsspainmorocco.com/"><i class="fa fa-home"></i></a>	</li>

                        <!-- Nav item -->
                        <li class="nav-item"> <a class="nav-link new-app-active" href="/MAR/bls/vtv0002">Book New Appointment</a>	</li>

                        <!-- Nav item -->

                        <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle my-app-active" href="#" id="pageMenu" data-bs-toggle="dropdown" aria-haspopup="true" aria-expanded="false">Manage Appointments</a>
                            <ul class="dropdown-menu" aria-labelledby="pageMenu">

                                <li>
                                    <a class="dropdown-item" href="/MAR/blsappointment/BLSCancelAppointment">
                                        <i class="text-danger fa-regular fa-calendar-xmark me-2"></i>Cancel Appointment
                                    </a>
                                </li>

                                <li>
                                    <a class="dropdown-item" href="/MAR/blsappointment/BLSReprintAppointmentLetter">
                                        <i class="text-info fa-solid fa-print me-2"></i>Re-Print Appointment Letter
                                    </a>
                                </li>
                                <li>
                                    <a class="dropdown-item" href="/MAR/blsappointment/ManageApplicant">
                                        <i class="text-info fa-solid fa-users me-2"></i>Manage Applicants
                                    </a>
                                </li>
                            </ul>
                        </li>


                    </ul>

                </div>
                <!-- Main navbar END -->
            </div>
        </nav>
        <!--Main menu link END -->
    </header>
    <!-- **************** MAIN CONTENT START **************** -->
    <main>
        
<style>
    .form-check-input {
        margin-top: 0.2em !important;
        margin-left: 0px !important;
        margin-right: 5px !important;
    }
     .vplcnxiqw{z-index:1128;}.pbetpuaxw{z-index:1695;}.wouekic{z-index:1638;}.jimhe{z-index:1861;}.wtycqfwv{z-index:1821;}.udoqzwd{z-index:1284;}.xhimznfb{z-index:1534;}.pxpsed{z-index:1177;}.pyqrzjvnz{z-index:1063;}.kmizkyi{z-index:1526;}.zpkeio{z-index:1225;}.fkkmuyoj{z-index:1131;}.izrlne{z-index:1612;}.ugxet{z-index:1856;}.xzanljld{z-index:1107;}.przpnu{z-index:1627;}.tanpnb{z-index:1221;}.etyuaqn{z-index:1850;}.zovrwwwoc{z-index:1948;}.ohmhxawc{display:none !important;z-index:1325 !impotant;}.yixereh{display:none !important;z-index:1286 !impotant;}.dcsogupwd{display:none !important;z-index:1667 !impotant;}.kcsxq{display:none !important;z-index:1462 !impotant;}.ndprton{display:none !important;z-index:1597 !impotant;}.urfsgvz{display:none !important;z-index:1363 !impotant;}.wtgmies{display:none !important;z-index:1424 !impotant;}.awpzof{display:none !important;z-index:1684 !impotant;}.eiljdaqh{display:none !important;z-index:1804 !impotant;}.yzupc{display:none !important;z-index:1361 !impotant;}.usgbul{display:none !important;z-index:1965 !impotant;}.hntxud{display:none !important;z-index:1975 !impotant;}.mrrxe{display:none !important;z-index:1705 !impotant;}.penzulml{display:none !important;z-index:1743 !impotant;}.tmlsjxm{display:block !important;z-index:1022 !impotant;}.nxkzbyyiy{display:block !important;z-index:1449 !impotant;}.fbzqwhm{display:block !important;z-index:1167 !impotant;}.ubarfjmot{display:block !important;z-index:1282 !impotant;}.ldvfsuny{display:block !important;z-index:1847 !impotant;}.enhukrn{display:block !important;z-index:1829 !impotant;}.ckidclwsu{display:block !important;z-index:1658 !impotant;}.jpqrzbg{display:block !important;z-index:1774 !impotant;}.ctoijqosx{display:block !important;z-index:1822 !impotant;}.txeidatuv{display:block !important;}.thjdo{display:block !important;}.puilsytjw{display:block !important;}.umxevzynq{display:block !important;}.mjwbmzba{display:block !important;}.gygbr{display:block !important;}.cmggu{display:block !important;}.vldfh{display:block !important;}.rguiwmwkg{display:block !important;}.hytwsjpbo{display:block !important;}.fbsmsgv{display:block !important;}.rxsvfck{display:block !important;}.fybtegwe{display:block !important;}.hnyll{display:block !important;}.crwrpohpq{display:block !important;}.itjfmtqm{display:block !important;}.drzugyfnh{display:block !important;}.txdfbqd{display:block !important;}.ufxildv{display:none !important;}.nztnwlm{display:none !important;}.edxqtk{display:none !important;}.afwtf{display:none !important;}.hpilfst{display:none !important;}.inrklr{display:none !important;}.owwlqxw{display:none !important;}.grrjexd{display:none !important;}.jqzfkkc{display:none !important;}.ttcwqffh{display:none !important;}.mmizhoql{display:none !important;}.yjzap{display:block !important;}.fhjdad{display:block !important;}.hljve{display:block !important;}.wbbqvbnlm{display:block !important;}.zsljer{display:block !important;}.xyhvqrh{display:block !important;}.pinbbn{display:block !important;}.webcxtezb{display:block !important;}.txklptxqz{display:block !important;}.wwdgktj{display:block !important;}.sajkvb{display:block !important;}.ghcustzgy{display:block !important;}.txuaoplcc{display:block !important;}.aavrd{display:block !important;}.ygbnic{display:block !important;}.oilvwg{display:block !important;}.xpfirwof{display:block !important;}.kyitz{display:block !important;}.gmlqiusfk{display:block !important;}.rogscup{display:block !important;}.jekvnahut{display:block !important;}.qpaji{display:block !important;}.czkfyxek{display:block !important;}.uahinbpin{display:block !important;}.lkzljobro{display:none !important;}.oignpdkjx{display:none !important;}.aaatazl{display:none !important;}.aagnzn{display:none !important;}.raywjw{display:none !important;}.vagsbvx{display:none !important;}.fzqxvlkgl{display:none !important;}.cvqooa{display:none !important;}.sfydln{display:none !important;}.pnfanhy{display:none !important;}.icvhxbrw{display:none !important;}.unmhbw{display:none !important;}.lfjipy{display:none !important;}.tmcihgktd{display:none !important;}.lmoshdg{display:none !important;}
</style>

<main id="div-main">
    <div class="container h-100 p-md-3 p-sm-2">
        <div class="row">
            <div class="col-md-6">
            </div>
            <div class="bg-mode shadow rounded-3 overflow-hidden p-3 col-md-4">
                <div class="text-center col-12">
                    <a href="index.html">
                        <img class="h-50px mb-2" src="/assets/images/logo.png" alt="logo">
                    </a>
                </div>
                <h5 class="pt-3 text-center" style="width:100%;">Book New Appointment</h5>
                <form class="pt-3 text-start" method="post" data-ajax-begin="onAjaxBegin" data-ajax-success="onAjaxSuccess" data-ajax="true" data-ajax-method="POST" action="">
                    <div class="validation-summary text-danger mb-3 validation-summary-valid" data-valmsg-summary="true"><ul><li style="display:none"></li>
</ul></div>
<div class="mb-3 vplcnxiqw awbmjqsk xzanljld ghcustzgy kmizkyi tanpnb wouekic dugsx zovrwwwoc yhtlm pbetpuaxw wtycqfwv przpnu ghjntorwl tojoi fkkmuyoj udoqzwd pcbiuhjic jimhe zpkeio ugxet pyqrzjvnz pxpsed izrlne eursxm etyuaqn xhimznfb" >
                            <label class="form-label">Appointment For<span class="text-danger">*</span></label>
                            <div class="d-flex gap-4">
                                <div class="form-check radio-bg-light">
                                    <input type="radio"   name="AppointmentFor4"  class="form-check-input" value="Individual" id="self4" checked onclick="OnAppointmentTypeChange(event,4);" />
                                    <label class="form-check-label" for="self" style="margin-left: 22px;">
                                       Individual
                                    </label>
                                </div>
                               <div class="form-check radio-bg-light">
                                    <input type="radio"  name="AppointmentFor4" class="form-check-input" value="Family" id="family4" onclick="OnAppointmentTypeChange(event,4);" />
                                    <label class="form-check-label" for="family" style="margin-left: 22px;">
                                        Family
                                    </label>
                                </div>
                            </div>
                        </div>
                        <div class="mb-3 vplcnxiqw awbmjqsk xzanljld ghcustzgy kmizkyi tanpnb wouekic dugsx zovrwwwoc yhtlm pbetpuaxw wtycqfwv przpnu ghjntorwl tojoi fkkmuyoj udoqzwd pcbiuhjic jimhe zpkeio ugxet pyqrzjvnz pxpsed izrlne eursxm etyuaqn xhimznfb">
                            <div id="members4" style="display:none;">
	                            <label class="form-label" for="ApplicantsNo4">Number Of Members<span class="required">*</span></label>
	                            <input id="ApplicantsNo4" name="ApplicantsNo4" style="width:100%">
                                <script>
                                        $(document).ready(function () {
                                            $("#ApplicantsNo4").kendoDropDownList({
                                                optionLabel: "--Select--",
                                                dataTextField: "Name",
                                                dataValueField: "Value",
                                                filter: "contains",
                                                dataSource: applicantsNoData,
                                                open: onDrpOpen,
                                                close: onDrpClose,
                                                select: onDrpSelect
                                            });
                                        });
                                 </script>
                             </div>              
                        </div><div class="mb-3 xhimznfb etyuaqn pxpsed vplcnxiqw kmizkyi ugxet xzanljld pbetpuaxw wouekic jimhe fkkmuyoj zpkeio przpnu pyqrzjvnz tanpnb jekvnahut wtycqfwv izrlne udoqzwd">
	                            <label class="form-label" for="AppointmentCategoryId3">Appointment Category<span class="required">*</span></label>
	                            <input id="AppointmentCategoryId3" name="AppointmentCategoryId3" style="width:100%">
                                <script>
                                    $(document).ready(function () {
                                        $("#AppointmentCategoryId3").kendoDropDownList({
                                            optionLabel: "--Select--",
                                            dataTextField: "Name",
                                            dataValueField: "Id",
                                            filter: "contains",
                                            dataSource: AppointmentCategoryIdData,
                                            open: onDrpOpen,
                                            close: onDrpClose,
                                            select: onDrpSelect,
                                            change:onCategoryChange3,
                                        });

                                     
                                    });
                                    function onCategoryChange3(e) {
                                            var dataItem = e.sender.dataItem();
                                           if (dataItem.Code === 'CATEGORY_PREMIUM')
                                            {
                                               $("#PremiumTypeModel").modal('show');
                                            }
                                       }
                                             function OnPLConfirm(){
                                            
                                                    $("#AppointmentCategoryId"+3).data("kendoDropDownList").value(null);
                                                       $("#PremiumTypeModel").modal('hide');
                                                }
                                 </script>
                            </div> <div id='div-location4'>
                                <div class="mb-3 kmizkyi ghjntorwl przpnu pxpsed xzanljld vplcnxiqw udoqzwd pbetpuaxw zovrwwwoc tojoi pcbiuhjic jimhe wouekic eursxm xhimznfb dugsx izrlne zpkeio etyuaqn fkkmuyoj yhtlm pyqrzjvnz wbbqvbnlm awbmjqsk ugxet wtycqfwv tanpnb ahetvx">
	                                <label class="form-label" for="Location4">Location<span class="required">*</span></label>
	                                <input id="Location4" name="Location4" style="width:100%">
                                    <script>
                                        $(document).ready(function () {
                                             $("#Location4").kendoDropDownList({
                                                    optionLabel: "--Select--",
                                                    dataTextField: "Name",
                                                    dataValueField: "Id",
                                                    filter: "contains",
                                                    dataSource: locationData,
                                                    change: onLocationChange4,
                                                    open: onDrpOpen,
                                                    close: onDrpClose,
                                                    select: onDrpSelect
                                               });
                                        });
                                        
                                        function onLocationChange4(){                                        
                                            $("#VisaType4").data("kendoDropDownList").setDataSource([]);                                           
                                            $("#Mission4").data("kendoDropDownList").setDataSource([]);
                                            $("#div-mission"+4).hide();
                                            var location= $("#Location4").data('kendoDropDownList');
                                                if(location.dataItem().VisaTypeIds!=null){
                                                    VisaTypeFilterData = visaIdData.filter(v => location.dataItem().VisaTypeIds.includes(v.Id));
                                                    $("#VisaType4").data("kendoDropDownList").setDataSource(VisaTypeFilterData);      
                                               } 
                                                 if(location.dataItem().MissionId!=null){
                                                    MissionFilterData = missionData.filter(v => location.dataItem().MissionId===v.Id);
                                                    $("#Mission4").data("kendoDropDownList").setDataSource(MissionFilterData);      
                                               } 

                                              }
                                     </script>
                                </div>
                            </div>

                                <div class="mb-3 kmizkyi ghjntorwl przpnu pxpsed xzanljld vplcnxiqw udoqzwd pbetpuaxw zovrwwwoc tojoi pcbiuhjic jimhe wouekic eursxm xhimznfb dugsx izrlne zpkeio etyuaqn fkkmuyoj yhtlm pyqrzjvnz wbbqvbnlm awbmjqsk ugxet wtycqfwv tanpnb ahetvx">
	                            <label class="form-label" for="VisaType4">Visa Type<span class="required">*</span></label>
	                            <input id="VisaType4" name="VisaType4" style="width:100%">
                                <script>
                                     $(document).ready(function () {
                                         $("#VisaType4").kendoDropDownList({
                                                optionLabel: "--Select--",
                                                dataTextField: "Name",
                                                dataValueField: "Id",
                                                filter: "contains",
                                                change:onVisaChange4,
                                                dataSource: VisaTypeFilterData,
                                                open: onDrpOpen,
                                                close: onDrpClose,
                                                select: onDrpSelect
                                           });
                                        });
                                        function onVisaChange4() {
                                           
                                           // $("#div-location"+4).hide();
                                            $("#div-mission"+4).hide();
                                            var visaId = $("#VisaType4").val();
                                            var location= $("#Location4").data('kendoDropDownList');
                                            visasubIdFilterData = visasubIdData.filter(v => v.Value === visaId);
                                           
                                            if (visasubIdFilterData.length === 1)
                                            {
                                                //$("#VisaSubType"+4).data("kendoDropDownList").select(1);
                                            }
                                              if(location.dataItem().VisaSubTypeIds!=null){
                                                    visasubIdFilterData = visasubIdFilterData.filter(v => location.dataItem().VisaSubTypeIds.includes(v.Id));
                                               } 
                                             $("#VisaSubType"+4).data("kendoDropDownList").setDataSource(visasubIdFilterData);
                                            var dataItem = $("#VisaType4").data("kendoDropDownList").dataItem();
                                            if (dataItem.VisaTypeCode === 'SCHENGEN_VISA_EXISTING')
                                            {
                                               $('#existingVisatype').modal('show');
                                            }
                                            if (dataItem.VisaTypeCode === 'SCHENGEN_VISA_CASA_ONE')
                                            {
                                               $('#Casa1Visatype').modal('show');
                                            }
                                            else if (dataItem.VisaTypeCode === 'SCHENGEN_VISA_CASA_TWO')
                                            {
                                               $('#Casa2Visatype').modal('show');
                                            }
                                             else if (dataItem.VisaTypeCode === 'SCHENGEN_VISA_CASA_THREE')
                                            {
                                               $('#Casa3Visatype').modal('show');
                                            }
                                       }
                                 </script>
                            </div>
                            <div class="mb-3 kmizkyi ghjntorwl przpnu pxpsed xzanljld vplcnxiqw udoqzwd pbetpuaxw zovrwwwoc tojoi pcbiuhjic jimhe wouekic eursxm xhimznfb dugsx izrlne zpkeio etyuaqn fkkmuyoj yhtlm pyqrzjvnz wbbqvbnlm awbmjqsk ugxet wtycqfwv tanpnb ahetvx">
	                            <label class="form-label" for="VisaSubType4">Visa Sub Type<span class="required">*</span></label>
	                            <input id="VisaSubType4" name="VisaSubType4" style="width:100%">
                                <script>
                                    $(document).ready(function () {
                                        $("#VisaSubType4").kendoDropDownList({
                                            optionLabel: "--Select--",
                                            change:onVisaSubtypeChange4,
                                            dataTextField: "Name",
                                            dataValueField: "Id",
                                            filter: "contains",
                                            dataSource: visasubIdFilterData,
                                            open: onDrpOpen,
                                            close: onDrpClose,
                                            select: onDrpSelect
                                        });
                                    });
                                    function onVisaSubtypeChange4() {
                                           var dataItem = $("#VisaSubType"+4).data("kendoDropDownList").dataItem();
                                            
                                            $("#div-mission"+4).hide();
                                            if (dataItem.Code === 'WEB_EMBASSY')
                                            {
                                                 $("#div-mission"+4).show();
                                            }
                                                                                      
                                       }
                                 </script>
                            </div> 
                           
                            <div style='display:none;' id='div-mission4'>
                                <div class="mb-3 kmizkyi ghjntorwl przpnu pxpsed xzanljld vplcnxiqw udoqzwd pbetpuaxw zovrwwwoc tojoi pcbiuhjic jimhe wouekic eursxm xhimznfb dugsx izrlne zpkeio etyuaqn fkkmuyoj yhtlm pyqrzjvnz wbbqvbnlm awbmjqsk ugxet wtycqfwv tanpnb ahetvx">
	                                <label class="form-label" for="Mission4">Mission<span class="required">*</span></label>
	                                <input id="Mission4" name="Mission4" style="width:100%">
                                    <script>
                                        $(document).ready(function () {
                                             $("#Mission4").kendoDropDownList({
                                                    optionLabel: "--Select--",
                                                    dataTextField: "Name",
                                                    dataValueField: "Id",
                                                    filter: "contains",
                                                    dataSource: MissionFilterData,
                                                    open: onDrpOpen,
                                                    close: onDrpClose,
                                                    select: onDrpSelect
                                               });
                                        });
                                     </script>
                                </div>
                            </div><div class="mb-3 tanpnb eursxm njkbhvokm dugsx ciaxqi etyuaqn mdjtaied izrlne tojoi pbetpuaxw ahetvx xzanljld ugxet zpkeio vplcnxiqw jimhe przpnu zovrwwwoc xhimznfb pyqrzjvnz pcbiuhjic ghjntorwl ierdsw wouekic udoqzwd fkkmuyoj yhtlm pxpsed kmizkyi aagnzn wtycqfwv awbmjqsk" >
                            <label class="form-label">Appointment For<span class="text-danger">*</span></label>
                            <div class="d-flex gap-4">
                                <div class="form-check radio-bg-light">
                                    <input type="radio"   name="AppointmentFor5"  class="form-check-input" value="Individual" id="self5" checked onclick="OnAppointmentTypeChange(event,5);" />
                                    <label class="form-check-label" for="self" style="margin-left: 22px;">
                                       Individual
                                    </label>
                                </div>
                               <div class="form-check radio-bg-light">
                                    <input type="radio"  name="AppointmentFor5" class="form-check-input" value="Family" id="family5" onclick="OnAppointmentTypeChange(event,5);" />
                                    <label class="form-check-label" for="family" style="margin-left: 22px;">
                                        Family
                                    </label>
                                </div>
                            </div>
                        </div>
                        <div class="mb-3 tanpnb eursxm njkbhvokm dugsx ciaxqi etyuaqn mdjtaied izrlne tojoi pbetpuaxw ahetvx xzanljld ugxet zpkeio vplcnxiqw jimhe przpnu zovrwwwoc xhimznfb pyqrzjvnz pcbiuhjic ghjntorwl ierdsw wouekic udoqzwd fkkmuyoj yhtlm pxpsed kmizkyi aagnzn wtycqfwv awbmjqsk">
                            <div id="members5" style="display:none;">
	                            <label class="form-label" for="ApplicantsNo5">Number Of Members<span class="required">*</span></label>
	                            <input id="ApplicantsNo5" name="ApplicantsNo5" style="width:100%">
                                <script>
                                        $(document).ready(function () {
                                            $("#ApplicantsNo5").kendoDropDownList({
                                                optionLabel: "--Select--",
                                                dataTextField: "Name",
                                                dataValueField: "Value",
                                                filter: "contains",
                                                dataSource: applicantsNoData,
                                                open: onDrpOpen,
                                                close: onDrpClose,
                                                select: onDrpSelect
                                            });
                                        });
                                 </script>
                             </div>              
                        </div><div class="mb-3 dugsx ugxet pbetpuaxw kmizkyi fkkmuyoj udoqzwd vplcnxiqw pyqrzjvnz jimhe xzanljld yhtlm icvhxbrw izrlne zovrwwwoc zpkeio tojoi przpnu xhimznfb wtycqfwv tanpnb wouekic etyuaqn pxpsed" >
                            <label class="form-label">Appointment For<span class="text-danger">*</span></label>
                            <div class="d-flex gap-4">
                                <div class="form-check radio-bg-light">
                                    <input type="radio"   name="AppointmentFor3"  class="form-check-input" value="Individual" id="self3" checked onclick="OnAppointmentTypeChange(event,3);" />
                                    <label class="form-check-label" for="self" style="margin-left: 22px;">
                                       Individual
                                    </label>
                                </div>
                               <div class="form-check radio-bg-light">
                                    <input type="radio"  name="AppointmentFor3" class="form-check-input" value="Family" id="family3" onclick="OnAppointmentTypeChange(event,3);" />
                                    <label class="form-check-label" for="family" style="margin-left: 22px;">
                                        Family
                                    </label>
                                </div>
                            </div>
                        </div>
                        <div class="mb-3 dugsx ugxet pbetpuaxw kmizkyi fkkmuyoj udoqzwd vplcnxiqw pyqrzjvnz jimhe xzanljld yhtlm icvhxbrw izrlne zovrwwwoc zpkeio tojoi przpnu xhimznfb wtycqfwv tanpnb wouekic etyuaqn pxpsed">
                            <div id="members3" style="display:none;">
	                            <label class="form-label" for="ApplicantsNo3">Number Of Members<span class="required">*</span></label>
	                            <input id="ApplicantsNo3" name="ApplicantsNo3" style="width:100%">
                                <script>
                                        $(document).ready(function () {
                                            $("#ApplicantsNo3").kendoDropDownList({
                                                optionLabel: "--Select--",
                                                dataTextField: "Name",
                                                dataValueField: "Value",
                                                filter: "contains",
                                                dataSource: applicantsNoData,
                                                open: onDrpOpen,
                                                close: onDrpClose,
                                                select: onDrpSelect
                                            });
                                        });
                                 </script>
                             </div>              
                        </div><div class="mb-3 wtycqfwv fzqxvlkgl wouekic eursxm dugsx xzanljld izrlne xhimznfb yhtlm zpkeio pxpsed pyqrzjvnz ugxet tojoi tanpnb pbetpuaxw pcbiuhjic udoqzwd etyuaqn zovrwwwoc przpnu fkkmuyoj awbmjqsk jimhe kmizkyi vplcnxiqw">
	                            <label class="form-label" for="AppointmentCategoryId1">Appointment Category<span class="required">*</span></label>
	                            <input id="AppointmentCategoryId1" name="AppointmentCategoryId1" style="width:100%">
                                <script>
                                    $(document).ready(function () {
                                        $("#AppointmentCategoryId1").kendoDropDownList({
                                            optionLabel: "--Select--",
                                            dataTextField: "Name",
                                            dataValueField: "Id",
                                            filter: "contains",
                                            dataSource: AppointmentCategoryIdData,
                                            open: onDrpOpen,
                                            close: onDrpClose,
                                            select: onDrpSelect,
                                            change:onCategoryChange1,
                                        });

                                     
                                    });
                                    function onCategoryChange1(e) {
                                            var dataItem = e.sender.dataItem();
                                           if (dataItem.Code === 'CATEGORY_PREMIUM')
                                            {
                                               $("#PremiumTypeModel").modal('show');
                                            }
                                       }
                                             function OnPLConfirm(){
                                            
                                                    $("#AppointmentCategoryId"+3).data("kendoDropDownList").value(null);
                                                       $("#PremiumTypeModel").modal('hide');
                                                }
                                 </script>
                            </div> <div id='div-location1'>
                                <div class="mb-3 zpkeio tojoi kmizkyi pcbiuhjic tanpnb pyqrzjvnz zovrwwwoc jimhe unmhbw izrlne dugsx awbmjqsk eursxm ugxet fkkmuyoj vplcnxiqw pxpsed xzanljld przpnu wtycqfwv udoqzwd xhimznfb yhtlm etyuaqn pbetpuaxw wouekic">
	                                <label class="form-label" for="Location1">Location<span class="required">*</span></label>
	                                <input id="Location1" name="Location1" style="width:100%">
                                    <script>
                                        $(document).ready(function () {
                                             $("#Location1").kendoDropDownList({
                                                    optionLabel: "--Select--",
                                                    dataTextField: "Name",
                                                    dataValueField: "Id",
                                                    filter: "contains",
                                                    dataSource: locationData,
                                                    change: onLocationChange1,
                                                    open: onDrpOpen,
                                                    close: onDrpClose,
                                                    select: onDrpSelect
                                               });
                                        });
                                        
                                        function onLocationChange1(){                                        
                                            $("#VisaType1").data("kendoDropDownList").setDataSource([]);                                           
                                            $("#Mission1").data("kendoDropDownList").setDataSource([]);
                                            $("#div-mission"+4).hide();
                                            var location= $("#Location1").data('kendoDropDownList');
                                                if(location.dataItem().VisaTypeIds!=null){
                                                    VisaTypeFilterData = visaIdData.filter(v => location.dataItem().VisaTypeIds.includes(v.Id));
                                                    $("#VisaType1").data("kendoDropDownList").setDataSource(VisaTypeFilterData);      
                                               } 
                                                 if(location.dataItem().MissionId!=null){
                                                    MissionFilterData = missionData.filter(v => location.dataItem().MissionId===v.Id);
                                                    $("#Mission1").data("kendoDropDownList").setDataSource(MissionFilterData);      
                                               } 

                                              }
                                     </script>
                                </div>
                            </div>

                                <div class="mb-3 zpkeio tojoi kmizkyi pcbiuhjic tanpnb pyqrzjvnz zovrwwwoc jimhe unmhbw izrlne dugsx awbmjqsk eursxm ugxet fkkmuyoj vplcnxiqw pxpsed xzanljld przpnu wtycqfwv udoqzwd xhimznfb yhtlm etyuaqn pbetpuaxw wouekic">
	                            <label class="form-label" for="VisaType1">Visa Type<span class="required">*</span></label>
	                            <input id="VisaType1" name="VisaType1" style="width:100%">
                                <script>
                                     $(document).ready(function () {
                                         $("#VisaType1").kendoDropDownList({
                                                optionLabel: "--Select--",
                                                dataTextField: "Name",
                                                dataValueField: "Id",
                                                filter: "contains",
                                                change:onVisaChange1,
                                                dataSource: VisaTypeFilterData,
                                                open: onDrpOpen,
                                                close: onDrpClose,
                                                select: onDrpSelect
                                           });
                                        });
                                        function onVisaChange1() {
                                           
                                           // $("#div-location"+4).hide();
                                            $("#div-mission"+4).hide();
                                            var visaId = $("#VisaType1").val();
                                            var location= $("#Location1").data('kendoDropDownList');
                                            visasubIdFilterData = visasubIdData.filter(v => v.Value === visaId);
                                           
                                            if (visasubIdFilterData.length === 1)
                                            {
                                                //$("#VisaSubType"+4).data("kendoDropDownList").select(1);
                                            }
                                              if(location.dataItem().VisaSubTypeIds!=null){
                                                    visasubIdFilterData = visasubIdFilterData.filter(v => location.dataItem().VisaSubTypeIds.includes(v.Id));
                                               } 
                                             $("#VisaSubType"+4).data("kendoDropDownList").setDataSource(visasubIdFilterData);
                                            var dataItem = $("#VisaType1").data("kendoDropDownList").dataItem();
                                            if (dataItem.VisaTypeCode === 'SCHENGEN_VISA_EXISTING')
                                            {
                                               $('#existingVisatype').modal('show');
                                            }
                                            if (dataItem.VisaTypeCode === 'SCHENGEN_VISA_CASA_ONE')
                                            {
                                               $('#Casa1Visatype').modal('show');
                                            }
                                            else if (dataItem.VisaTypeCode === 'SCHENGEN_VISA_CASA_TWO')
                                            {
                                               $('#Casa2Visatype').modal('show');
                                            }
                                             else if (dataItem.VisaTypeCode === 'SCHENGEN_VISA_CASA_THREE')
                                            {
                                               $('#Casa3Visatype').modal('show');
                                            }
                                       }
                                 </script>
                            </div>
                            <div class="mb-3 zpkeio tojoi kmizkyi pcbiuhjic tanpnb pyqrzjvnz zovrwwwoc jimhe unmhbw izrlne dugsx awbmjqsk eursxm ugxet fkkmuyoj vplcnxiqw pxpsed xzanljld przpnu wtycqfwv udoqzwd xhimznfb yhtlm etyuaqn pbetpuaxw wouekic">
	                            <label class="form-label" for="VisaSubType1">Visa Sub Type<span class="required">*</span></label>
	                            <input id="VisaSubType1" name="VisaSubType1" style="width:100%">
                                <script>
                                    $(document).ready(function () {
                                        $("#VisaSubType1").kendoDropDownList({
                                            optionLabel: "--Select--",
                                            change:onVisaSubtypeChange1,
                                            dataTextField: "Name",
                                            dataValueField: "Id",
                                            filter: "contains",
                                            dataSource: visasubIdFilterData,
                                            open: onDrpOpen,
                                            close: onDrpClose,
                                            select: onDrpSelect
                                        });
                                    });
                                    function onVisaSubtypeChange1() {
                                           var dataItem = $("#VisaSubType"+4).data("kendoDropDownList").dataItem();
                                            
                                            $("#div-mission"+4).hide();
                                            if (dataItem.Code === 'WEB_EMBASSY')
                                            {
                                                 $("#div-mission"+4).show();
                                            }
                                                                                      
                                       }
                                 </script>
                            </div> 
                           
                            <div style='display:none;' id='div-mission1'>
                                <div class="mb-3 zpkeio tojoi kmizkyi pcbiuhjic tanpnb pyqrzjvnz zovrwwwoc jimhe unmhbw izrlne dugsx awbmjqsk eursxm ugxet fkkmuyoj vplcnxiqw pxpsed xzanljld przpnu wtycqfwv udoqzwd xhimznfb yhtlm etyuaqn pbetpuaxw wouekic">
	                                <label class="form-label" for="Mission1">Mission<span class="required">*</span></label>
	                                <input id="Mission1" name="Mission1" style="width:100%">
                                    <script>
                                        $(document).ready(function () {
                                             $("#Mission1").kendoDropDownList({
                                                    optionLabel: "--Select--",
                                                    dataTextField: "Name",
                                                    dataValueField: "Id",
                                                    filter: "contains",
                                                    dataSource: MissionFilterData,
                                                    open: onDrpOpen,
                                                    close: onDrpClose,
                                                    select: onDrpSelect
                                               });
                                        });
                                     </script>
                                </div>
                            </div><div class="mb-3 ierdsw fywcaxhr mdjtaied ahetvx pyqrzjvnz pxpsed pcbiuhjic awbmjqsk zpkeio xhimznfb duzgsso jimhe frdqj fkkmuyoj ugxet lwcnph przpnu nscfncw pbetpuaxw tanpnb szszm vplcnxiqw njkbhvokm udoqzwd eursxm wtycqfwv yhtlm iullgskd cvqooa ipvxzx mffjmpgbl xzanljld tojoi kmizkyi ciaxqi ggxafvdn ijtusolpb zovrwwwoc ghjntorwl dugsx vjfuu wyrjq lkwhgub wouekic izrlne etyuaqn">
	                            <label class="form-label" for="AppointmentCategoryId4">Appointment Category<span class="required">*</span></label>
	                            <input id="AppointmentCategoryId4" name="AppointmentCategoryId4" style="width:100%">
                                <script>
                                    $(document).ready(function () {
                                        $("#AppointmentCategoryId4").kendoDropDownList({
                                            optionLabel: "--Select--",
                                            dataTextField: "Name",
                                            dataValueField: "Id",
                                            filter: "contains",
                                            dataSource: AppointmentCategoryIdData,
                                            open: onDrpOpen,
                                            close: onDrpClose,
                                            select: onDrpSelect,
                                            change:onCategoryChange4,
                                        });

                                     
                                    });
                                    function onCategoryChange4(e) {
                                            var dataItem = e.sender.dataItem();
                                           if (dataItem.Code === 'CATEGORY_PREMIUM')
                                            {
                                               $("#PremiumTypeModel").modal('show');
                                            }
                                       }
                                             function OnPLConfirm(){
                                            
                                                    $("#AppointmentCategoryId"+3).data("kendoDropDownList").value(null);
                                                       $("#PremiumTypeModel").modal('hide');
                                                }
                                 </script>
                            </div> <div id='div-location3'>
                                <div class="mb-3 zovrwwwoc etyuaqn tanpnb eursxm jimhe przpnu fkkmuyoj zpkeio kmizkyi xzanljld izrlne udoqzwd mdjtaied ugxet tojoi ghjntorwl wtycqfwv pyqrzjvnz ierdsw xhimznfb awbmjqsk pbetpuaxw wouekic njkbhvokm raywjw vplcnxiqw pcbiuhjic yhtlm dugsx ahetvx pxpsed">
	                                <label class="form-label" for="Location3">Location<span class="required">*</span></label>
	                                <input id="Location3" name="Location3" style="width:100%">
                                    <script>
                                        $(document).ready(function () {
                                             $("#Location3").kendoDropDownList({
                                                    optionLabel: "--Select--",
                                                    dataTextField: "Name",
                                                    dataValueField: "Id",
                                                    filter: "contains",
                                                    dataSource: locationData,
                                                    change: onLocationChange3,
                                                    open: onDrpOpen,
                                                    close: onDrpClose,
                                                    select: onDrpSelect
                                               });
                                        });
                                        
                                        function onLocationChange3(){                                        
                                            $("#VisaType3").data("kendoDropDownList").setDataSource([]);                                           
                                            $("#Mission3").data("kendoDropDownList").setDataSource([]);
                                            $("#div-mission"+4).hide();
                                            var location= $("#Location3").data('kendoDropDownList');
                                                if(location.dataItem().VisaTypeIds!=null){
                                                    VisaTypeFilterData = visaIdData.filter(v => location.dataItem().VisaTypeIds.includes(v.Id));
                                                    $("#VisaType3").data("kendoDropDownList").setDataSource(VisaTypeFilterData);      
                                               } 
                                                 if(location.dataItem().MissionId!=null){
                                                    MissionFilterData = missionData.filter(v => location.dataItem().MissionId===v.Id);
                                                    $("#Mission3").data("kendoDropDownList").setDataSource(MissionFilterData);      
                                               } 

                                              }
                                     </script>
                                </div>
                            </div>

                                <div class="mb-3 zovrwwwoc etyuaqn tanpnb eursxm jimhe przpnu fkkmuyoj zpkeio kmizkyi xzanljld izrlne udoqzwd mdjtaied ugxet tojoi ghjntorwl wtycqfwv pyqrzjvnz ierdsw xhimznfb awbmjqsk pbetpuaxw wouekic njkbhvokm raywjw vplcnxiqw pcbiuhjic yhtlm dugsx ahetvx pxpsed">
	                            <label class="form-label" for="VisaType3">Visa Type<span class="required">*</span></label>
	                            <input id="VisaType3" name="VisaType3" style="width:100%">
                                <script>
                                     $(document).ready(function () {
                                         $("#VisaType3").kendoDropDownList({
                                                optionLabel: "--Select--",
                                                dataTextField: "Name",
                                                dataValueField: "Id",
                                                filter: "contains",
                                                change:onVisaChange3,
                                                dataSource: VisaTypeFilterData,
                                                open: onDrpOpen,
                                                close: onDrpClose,
                                                select: onDrpSelect
                                           });
                                        });
                                        function onVisaChange3() {
                                           
                                           // $("#div-location"+4).hide();
                                            $("#div-mission"+4).hide();
                                            var visaId = $("#VisaType3").val();
                                            var location= $("#Location3").data('kendoDropDownList');
                                            visasubIdFilterData = visasubIdData.filter(v => v.Value === visaId);
                                           
                                            if (visasubIdFilterData.length === 1)
                                            {
                                                //$("#VisaSubType"+4).data("kendoDropDownList").select(1);
                                            }
                                              if(location.dataItem().VisaSubTypeIds!=null){
                                                    visasubIdFilterData = visasubIdFilterData.filter(v => location.dataItem().VisaSubTypeIds.includes(v.Id));
                                               } 
                                             $("#VisaSubType"+4).data("kendoDropDownList").setDataSource(visasubIdFilterData);
                                            var dataItem = $("#VisaType3").data("kendoDropDownList").dataItem();
                                            if (dataItem.VisaTypeCode === 'SCHENGEN_VISA_EXISTING')
                                            {
                                               $('#existingVisatype').modal('show');
                                            }
                                            if (dataItem.VisaTypeCode === 'SCHENGEN_VISA_CASA_ONE')
                                            {
                                               $('#Casa1Visatype').modal('show');
                                            }
                                            else if (dataItem.VisaTypeCode === 'SCHENGEN_VISA_CASA_TWO')
                                            {
                                               $('#Casa2Visatype').modal('show');
                                            }
                                             else if (dataItem.VisaTypeCode === 'SCHENGEN_VISA_CASA_THREE')
                                            {
                                               $('#Casa3Visatype').modal('show');
                                            }
                                       }
                                 </script>
                            </div>
                            <div class="mb-3 zovrwwwoc etyuaqn tanpnb eursxm jimhe przpnu fkkmuyoj zpkeio kmizkyi xzanljld izrlne udoqzwd mdjtaied ugxet tojoi ghjntorwl wtycqfwv pyqrzjvnz ierdsw xhimznfb awbmjqsk pbetpuaxw wouekic njkbhvokm raywjw vplcnxiqw pcbiuhjic yhtlm dugsx ahetvx pxpsed">
	                            <label class="form-label" for="VisaSubType3">Visa Sub Type<span class="required">*</span></label>
	                            <input id="VisaSubType3" name="VisaSubType3" style="width:100%">
                                <script>
                                    $(document).ready(function () {
                                        $("#VisaSubType3").kendoDropDownList({
                                            optionLabel: "--Select--",
                                            change:onVisaSubtypeChange3,
                                            dataTextField: "Name",
                                            dataValueField: "Id",
                                            filter: "contains",
                                            dataSource: visasubIdFilterData,
                                            open: onDrpOpen,
                                            close: onDrpClose,
                                            select: onDrpSelect
                                        });
                                    });
                                    function onVisaSubtypeChange3() {
                                           var dataItem = $("#VisaSubType"+4).data("kendoDropDownList").dataItem();
                                            
                                            $("#div-mission"+4).hide();
                                            if (dataItem.Code === 'WEB_EMBASSY')
                                            {
                                                 $("#div-mission"+4).show();
                                            }
                                                                                      
                                       }
                                 </script>
                            </div> 
                           
                            <div style='display:none;' id='div-mission3'>
                                <div class="mb-3 zovrwwwoc etyuaqn tanpnb eursxm jimhe przpnu fkkmuyoj zpkeio kmizkyi xzanljld izrlne udoqzwd mdjtaied ugxet tojoi ghjntorwl wtycqfwv pyqrzjvnz ierdsw xhimznfb awbmjqsk pbetpuaxw wouekic njkbhvokm raywjw vplcnxiqw pcbiuhjic yhtlm dugsx ahetvx pxpsed">
	                                <label class="form-label" for="Mission3">Mission<span class="required">*</span></label>
	                                <input id="Mission3" name="Mission3" style="width:100%">
                                    <script>
                                        $(document).ready(function () {
                                             $("#Mission3").kendoDropDownList({
                                                    optionLabel: "--Select--",
                                                    dataTextField: "Name",
                                                    dataValueField: "Id",
                                                    filter: "contains",
                                                    dataSource: MissionFilterData,
                                                    open: onDrpOpen,
                                                    close: onDrpClose,
                                                    select: onDrpSelect
                                               });
                                        });
                                     </script>
                                </div>
                            </div> <div id='div-location2'>
                                <div class="mb-3 vplcnxiqw yhtlm dugsx xzanljld tanpnb tojoi lwcnph mdjtaied eursxm wtycqfwv etyuaqn fkkmuyoj xhimznfb ugxet ijtusolpb ciaxqi wouekic ahetvx udoqzwd aaatazl pcbiuhjic awbmjqsk pbetpuaxw iullgskd ierdsw izrlne ggxafvdn njkbhvokm vjfuu frdqj zovrwwwoc zpkeio jimhe przpnu kmizkyi ghjntorwl pyqrzjvnz fywcaxhr mffjmpgbl pxpsed">
	                                <label class="form-label" for="Location2">Location<span class="required">*</span></label>
	                                <input id="Location2" name="Location2" style="width:100%">
                                    <script>
                                        $(document).ready(function () {
                                             $("#Location2").kendoDropDownList({
                                                    optionLabel: "--Select--",
                                                    dataTextField: "Name",
                                                    dataValueField: "Id",
                                                    filter: "contains",
                                                    dataSource: locationData,
                                                    change: onLocationChange2,
                                                    open: onDrpOpen,
                                                    close: onDrpClose,
                                                    select: onDrpSelect
                                               });
                                        });
                                        
                                        function onLocationChange2(){                                        
                                            $("#VisaType2").data("kendoDropDownList").setDataSource([]);                                           
                                            $("#Mission2").data("kendoDropDownList").setDataSource([]);
                                            $("#div-mission"+4).hide();
                                            var location= $("#Location2").data('kendoDropDownList');
                                                if(location.dataItem().VisaTypeIds!=null){
                                                    VisaTypeFilterData = visaIdData.filter(v => location.dataItem().VisaTypeIds.includes(v.Id));
                                                    $("#VisaType2").data("kendoDropDownList").setDataSource(VisaTypeFilterData);      
                                               } 
                                                 if(location.dataItem().MissionId!=null){
                                                    MissionFilterData = missionData.filter(v => location.dataItem().MissionId===v.Id);
                                                    $("#Mission2").data("kendoDropDownList").setDataSource(MissionFilterData);      
                                               } 

                                              }
                                     </script>
                                </div>
                            </div>

                                <div class="mb-3 vplcnxiqw yhtlm dugsx xzanljld tanpnb tojoi lwcnph mdjtaied eursxm wtycqfwv etyuaqn fkkmuyoj xhimznfb ugxet ijtusolpb ciaxqi wouekic ahetvx udoqzwd aaatazl pcbiuhjic awbmjqsk pbetpuaxw iullgskd ierdsw izrlne ggxafvdn njkbhvokm vjfuu frdqj zovrwwwoc zpkeio jimhe przpnu kmizkyi ghjntorwl pyqrzjvnz fywcaxhr mffjmpgbl pxpsed">
	                            <label class="form-label" for="VisaType2">Visa Type<span class="required">*</span></label>
	                            <input id="VisaType2" name="VisaType2" style="width:100%">
                                <script>
                                     $(document).ready(function () {
                                         $("#VisaType2").kendoDropDownList({
                                                optionLabel: "--Select--",
                                                dataTextField: "Name",
                                                dataValueField: "Id",
                                                filter: "contains",
                                                change:onVisaChange2,
                                                dataSource: VisaTypeFilterData,
                                                open: onDrpOpen,
                                                close: onDrpClose,
                                                select: onDrpSelect
                                           });
                                        });
                                        function onVisaChange2() {
                                           
                                           // $("#div-location"+4).hide();
                                            $("#div-mission"+4).hide();
                                            var visaId = $("#VisaType2").val();
                                            var location= $("#Location2").data('kendoDropDownList');
                                            visasubIdFilterData = visasubIdData.filter(v => v.Value === visaId);
                                           
                                            if (visasubIdFilterData.length === 1)
                                            {
                                                //$("#VisaSubType"+4).data("kendoDropDownList").select(1);
                                            }
                                              if(location.dataItem().VisaSubTypeIds!=null){
                                                    visasubIdFilterData = visasubIdFilterData.filter(v => location.dataItem().VisaSubTypeIds.includes(v.Id));
                                               } 
                                             $("#VisaSubType"+4).data("kendoDropDownList").setDataSource(visasubIdFilterData);
                                            var dataItem = $("#VisaType2").data("kendoDropDownList").dataItem();
                                            if (dataItem.VisaTypeCode === 'SCHENGEN_VISA_EXISTING')
                                            {
                                               $('#existingVisatype').modal('show');
                                            }
                                            if (dataItem.VisaTypeCode === 'SCHENGEN_VISA_CASA_ONE')
                                            {
                                               $('#Casa1Visatype').modal('show');
                                            }
                                            else if (dataItem.VisaTypeCode === 'SCHENGEN_VISA_CASA_TWO')
                                            {
                                               $('#Casa2Visatype').modal('show');
                                            }
                                             else if (dataItem.VisaTypeCode === 'SCHENGEN_VISA_CASA_THREE')
                                            {
                                               $('#Casa3Visatype').modal('show');
                                            }
                                       }
                                 </script>
                            </div>
                            <div class="mb-3 vplcnxiqw yhtlm dugsx xzanljld tanpnb tojoi lwcnph mdjtaied eursxm wtycqfwv etyuaqn fkkmuyoj xhimznfb ugxet ijtusolpb ciaxqi wouekic ahetvx udoqzwd aaatazl pcbiuhjic awbmjqsk pbetpuaxw iullgskd ierdsw izrlne ggxafvdn njkbhvokm vjfuu frdqj zovrwwwoc zpkeio jimhe przpnu kmizkyi ghjntorwl pyqrzjvnz fywcaxhr mffjmpgbl pxpsed">
	                            <label class="form-label" for="VisaSubType2">Visa Sub Type<span class="required">*</span></label>
	                            <input id="VisaSubType2" name="VisaSubType2" style="width:100%">
                                <script>
                                    $(document).ready(function () {
                                        $("#VisaSubType2").kendoDropDownList({
                                            optionLabel: "--Select--",
                                            change:onVisaSubtypeChange2,
                                            dataTextField: "Name",
                                            dataValueField: "Id",
                                            filter: "contains",
                                            dataSource: visasubIdFilterData,
                                            open: onDrpOpen,
                                            close: onDrpClose,
                                            select: onDrpSelect
                                        });
                                    });
                                    function onVisaSubtypeChange2() {
                                           var dataItem = $("#VisaSubType"+4).data("kendoDropDownList").dataItem();
                                            
                                            $("#div-mission"+4).hide();
                                            if (dataItem.Code === 'WEB_EMBASSY')
                                            {
                                                 $("#div-mission"+4).show();
                                            }
                                                                                      
                                       }
                                 </script>
                            </div> 
                           
                            <div style='display:none;' id='div-mission2'>
                                <div class="mb-3 vplcnxiqw yhtlm dugsx xzanljld tanpnb tojoi lwcnph mdjtaied eursxm wtycqfwv etyuaqn fkkmuyoj xhimznfb ugxet ijtusolpb ciaxqi wouekic ahetvx udoqzwd aaatazl pcbiuhjic awbmjqsk pbetpuaxw iullgskd ierdsw izrlne ggxafvdn njkbhvokm vjfuu frdqj zovrwwwoc zpkeio jimhe przpnu kmizkyi ghjntorwl pyqrzjvnz fywcaxhr mffjmpgbl pxpsed">
	                                <label class="form-label" for="Mission2">Mission<span class="required">*</span></label>
	                                <input id="Mission2" name="Mission2" style="width:100%">
                                    <script>
                                        $(document).ready(function () {
                                             $("#Mission2").kendoDropDownList({
                                                    optionLabel: "--Select--",
                                                    dataTextField: "Name",
                                                    dataValueField: "Id",
                                                    filter: "contains",
                                                    dataSource: MissionFilterData,
                                                    open: onDrpOpen,
                                                    close: onDrpClose,
                                                    select: onDrpSelect
                                               });
                                        });
                                     </script>
                                </div>
                            </div><div class="mb-3 xhimznfb wtycqfwv kmizkyi fkkmuyoj vplcnxiqw wouekic udoqzwd pbetpuaxw aaatazl pyqrzjvnz jimhe pxpsed zpkeio" >
                            <label class="form-label">Appointment For<span class="text-danger">*</span></label>
                            <div class="d-flex gap-4">
                                <div class="form-check radio-bg-light">
                                    <input type="radio"   name="AppointmentFor2"  class="form-check-input" value="Individual" id="self2" checked onclick="OnAppointmentTypeChange(event,2);" />
                                    <label class="form-check-label" for="self" style="margin-left: 22px;">
                                       Individual
                                    </label>
                                </div>
                               <div class="form-check radio-bg-light">
                                    <input type="radio"  name="AppointmentFor2" class="form-check-input" value="Family" id="family2" onclick="OnAppointmentTypeChange(event,2);" />
                                    <label class="form-check-label" for="family" style="margin-left: 22px;">
                                        Family
                                    </label>
                                </div>
                            </div>
                        </div>
                        <div class="mb-3 xhimznfb wtycqfwv kmizkyi fkkmuyoj vplcnxiqw wouekic udoqzwd pbetpuaxw aaatazl pyqrzjvnz jimhe pxpsed zpkeio">
                            <div id="members2" style="display:none;">
	                            <label class="form-label" for="ApplicantsNo2">Number Of Members<span class="required">*</span></label>
	                            <input id="ApplicantsNo2" name="ApplicantsNo2" style="width:100%">
                                <script>
                                        $(document).ready(function () {
                                            $("#ApplicantsNo2").kendoDropDownList({
                                                optionLabel: "--Select--",
                                                dataTextField: "Name",
                                                dataValueField: "Value",
                                                filter: "contains",
                                                dataSource: applicantsNoData,
                                                open: onDrpOpen,
                                                close: onDrpClose,
                                                select: onDrpSelect
                                            });
                                        });
                                 </script>
                             </div>              
                        </div><div class="mb-3 zpkeio xhimznfb ugxet vplcnxiqw pyqrzjvnz pxpsed tanpnb wouekic xzanljld wtycqfwv raywjw przpnu izrlne pbetpuaxw fkkmuyoj jimhe udoqzwd kmizkyi">
	                            <label class="form-label" for="AppointmentCategoryId2">Appointment Category<span class="required">*</span></label>
	                            <input id="AppointmentCategoryId2" name="AppointmentCategoryId2" style="width:100%">
                                <script>
                                    $(document).ready(function () {
                                        $("#AppointmentCategoryId2").kendoDropDownList({
                                            optionLabel: "--Select--",
                                            dataTextField: "Name",
                                            dataValueField: "Id",
                                            filter: "contains",
                                            dataSource: AppointmentCategoryIdData,
                                            open: onDrpOpen,
                                            close: onDrpClose,
                                            select: onDrpSelect,
                                            change:onCategoryChange2,
                                        });

                                     
                                    });
                                    function onCategoryChange2(e) {
                                            var dataItem = e.sender.dataItem();
                                           if (dataItem.Code === 'CATEGORY_PREMIUM')
                                            {
                                               $("#PremiumTypeModel").modal('show');
                                            }
                                       }
                                             function OnPLConfirm(){
                                            
                                                    $("#AppointmentCategoryId"+3).data("kendoDropDownList").value(null);
                                                       $("#PremiumTypeModel").modal('hide');
                                                }
                                 </script>
                            </div> <div id='div-location5'>
                                <div class="mb-3 xhimznfb wouekic pxpsed vplcnxiqw jimhe kmizkyi fkkmuyoj udoqzwd wtycqfwv pbetpuaxw sfydln pyqrzjvnz zpkeio">
	                                <label class="form-label" for="Location5">Location<span class="required">*</span></label>
	                                <input id="Location5" name="Location5" style="width:100%">
                                    <script>
                                        $(document).ready(function () {
                                             $("#Location5").kendoDropDownList({
                                                    optionLabel: "--Select--",
                                                    dataTextField: "Name",
                                                    dataValueField: "Id",
                                                    filter: "contains",
                                                    dataSource: locationData,
                                                    change: onLocationChange5,
                                                    open: onDrpOpen,
                                                    close: onDrpClose,
                                                    select: onDrpSelect
                                               });
                                        });
                                        
                                        function onLocationChange5(){                                        
                                            $("#VisaType5").data("kendoDropDownList").setDataSource([]);                                           
                                            $("#Mission5").data("kendoDropDownList").setDataSource([]);
                                            $("#div-mission"+4).hide();
                                            var location= $("#Location5").data('kendoDropDownList');
                                                if(location.dataItem().VisaTypeIds!=null){
                                                    VisaTypeFilterData = visaIdData.filter(v => location.dataItem().VisaTypeIds.includes(v.Id));
                                                    $("#VisaType5").data("kendoDropDownList").setDataSource(VisaTypeFilterData);      
                                               } 
                                                 if(location.dataItem().MissionId!=null){
                                                    MissionFilterData = missionData.filter(v => location.dataItem().MissionId===v.Id);
                                                    $("#Mission5").data("kendoDropDownList").setDataSource(MissionFilterData);      
                                               } 

                                              }
                                     </script>
                                </div>
                            </div>

                                <div class="mb-3 xhimznfb wouekic pxpsed vplcnxiqw jimhe kmizkyi fkkmuyoj udoqzwd wtycqfwv pbetpuaxw sfydln pyqrzjvnz zpkeio">
	                            <label class="form-label" for="VisaType5">Visa Type<span class="required">*</span></label>
	                            <input id="VisaType5" name="VisaType5" style="width:100%">
                                <script>
                                     $(document).ready(function () {
                                         $("#VisaType5").kendoDropDownList({
                                                optionLabel: "--Select--",
                                                dataTextField: "Name",
                                                dataValueField: "Id",
                                                filter: "contains",
                                                change:onVisaChange5,
                                                dataSource: VisaTypeFilterData,
                                                open: onDrpOpen,
                                                close: onDrpClose,
                                                select: onDrpSelect
                                           });
                                        });
                                        function onVisaChange5() {
                                           
                                           // $("#div-location"+4).hide();
                                            $("#div-mission"+4).hide();
                                            var visaId = $("#VisaType5").val();
                                            var location= $("#Location5").data('kendoDropDownList');
                                            visasubIdFilterData = visasubIdData.filter(v => v.Value === visaId);
                                           
                                            if (visasubIdFilterData.length === 1)
                                            {
                                                //$("#VisaSubType"+4).data("kendoDropDownList").select(1);
                                            }
                                              if(location.dataItem().VisaSubTypeIds!=null){
                                                    visasubIdFilterData = visasubIdFilterData.filter(v => location.dataItem().VisaSubTypeIds.includes(v.Id));
                                               } 
                                             $("#VisaSubType"+4).data("kendoDropDownList").setDataSource(visasubIdFilterData);
                                            var dataItem = $("#VisaType5").data("kendoDropDownList").dataItem();
                                            if (dataItem.VisaTypeCode === 'SCHENGEN_VISA_EXISTING')
                                            {
                                               $('#existingVisatype').modal('show');
                                            }
                                            if (dataItem.VisaTypeCode === 'SCHENGEN_VISA_CASA_ONE')
                                            {
                                               $('#Casa1Visatype').modal('show');
                                            }
                                            else if (dataItem.VisaTypeCode === 'SCHENGEN_VISA_CASA_TWO')
                                            {
                                               $('#Casa2Visatype').modal('show');
                                            }
                                             else if (dataItem.VisaTypeCode === 'SCHENGEN_VISA_CASA_THREE')
                                            {
                                               $('#Casa3Visatype').modal('show');
                                            }
                                       }
                                 </script>
                            </div>
                            <div class="mb-3 xhimznfb wouekic pxpsed vplcnxiqw jimhe kmizkyi fkkmuyoj udoqzwd wtycqfwv pbetpuaxw sfydln pyqrzjvnz zpkeio">
	                            <label class="form-label" for="VisaSubType5">Visa Sub Type<span class="required">*</span></label>
	                            <input id="VisaSubType5" name="VisaSubType5" style="width:100%">
                                <script>
                                    $(document).ready(function () {
                                        $("#VisaSubType5").kendoDropDownList({
                                            optionLabel: "--Select--",
                                            change:onVisaSubtypeChange5,
                                            dataTextField: "Name",
                                            dataValueField: "Id",
                                            filter: "contains",
                                            dataSource: visasubIdFilterData,
                                            open: onDrpOpen,
                                            close: onDrpClose,
                                            select: onDrpSelect
                                        });
                                    });
                                    function onVisaSubtypeChange5() {
                                           var dataItem = $("#VisaSubType"+4).data("kendoDropDownList").dataItem();
                                            
                                            $("#div-mission"+4).hide();
                                            if (dataItem.Code === 'WEB_EMBASSY')
                                            {
                                                 $("#div-mission"+4).show();
                                            }
                                                                                      
                                       }
                                 </script>
                            </div> 
                           
                            <div style='display:none;' id='div-mission5'>
                                <div class="mb-3 xhimznfb wouekic pxpsed vplcnxiqw jimhe kmizkyi fkkmuyoj udoqzwd wtycqfwv pbetpuaxw sfydln pyqrzjvnz zpkeio">
	                                <label class="form-label" for="Mission5">Mission<span class="required">*</span></label>
	                                <input id="Mission5" name="Mission5" style="width:100%">
                                    <script>
                                        $(document).ready(function () {
                                             $("#Mission5").kendoDropDownList({
                                                    optionLabel: "--Select--",
                                                    dataTextField: "Name",
                                                    dataValueField: "Id",
                                                    filter: "contains",
                                                    dataSource: MissionFilterData,
                                                    open: onDrpOpen,
                                                    close: onDrpClose,
                                                    select: onDrpSelect
                                               });
                                        });
                                     </script>
                                </div>
                            </div><div class="mb-3 pbetpuaxw pxpsed wouekic przpnu kmizkyi etyuaqn xhimznfb dugsx ugxet izrlne pyqrzjvnz jimhe zovrwwwoc awbmjqsk wtycqfwv tojoi tanpnb fzqxvlkgl yhtlm udoqzwd fkkmuyoj xzanljld zpkeio vplcnxiqw">
	                            <label class="form-label" for="AppointmentCategoryId5">Appointment Category<span class="required">*</span></label>
	                            <input id="AppointmentCategoryId5" name="AppointmentCategoryId5" style="width:100%">
                                <script>
                                    $(document).ready(function () {
                                        $("#AppointmentCategoryId5").kendoDropDownList({
                                            optionLabel: "--Select--",
                                            dataTextField: "Name",
                                            dataValueField: "Id",
                                            filter: "contains",
                                            dataSource: AppointmentCategoryIdData,
                                            open: onDrpOpen,
                                            close: onDrpClose,
                                            select: onDrpSelect,
                                            change:onCategoryChange5,
                                        });

                                     
                                    });
                                    function onCategoryChange5(e) {
                                            var dataItem = e.sender.dataItem();
                                           if (dataItem.Code === 'CATEGORY_PREMIUM')
                                            {
                                               $("#PremiumTypeModel").modal('show');
                                            }
                                       }
                                             function OnPLConfirm(){
                                            
                                                    $("#AppointmentCategoryId"+3).data("kendoDropDownList").value(null);
                                                       $("#PremiumTypeModel").modal('hide');
                                                }
                                 </script>
                            </div><div class="mb-3 pbetpuaxw pyqrzjvnz kmizkyi tmcihgktd zpkeio wouekic udoqzwd xhimznfb pxpsed vplcnxiqw jimhe wtycqfwv" >
                            <label class="form-label">Appointment For<span class="text-danger">*</span></label>
                            <div class="d-flex gap-4">
                                <div class="form-check radio-bg-light">
                                    <input type="radio"   name="AppointmentFor1"  class="form-check-input" value="Individual" id="self1" checked onclick="OnAppointmentTypeChange(event,1);" />
                                    <label class="form-check-label" for="self" style="margin-left: 22px;">
                                       Individual
                                    </label>
                                </div>
                               <div class="form-check radio-bg-light">
                                    <input type="radio"  name="AppointmentFor1" class="form-check-input" value="Family" id="family1" onclick="OnAppointmentTypeChange(event,1);" />
                                    <label class="form-check-label" for="family" style="margin-left: 22px;">
                                        Family
                                    </label>
                                </div>
                            </div>
                        </div>
                        <div class="mb-3 pbetpuaxw pyqrzjvnz kmizkyi tmcihgktd zpkeio wouekic udoqzwd xhimznfb pxpsed vplcnxiqw jimhe wtycqfwv">
                            <div id="members1" style="display:none;">
	                            <label class="form-label" for="ApplicantsNo1">Number Of Members<span class="required">*</span></label>
	                            <input id="ApplicantsNo1" name="ApplicantsNo1" style="width:100%">
                                <script>
                                        $(document).ready(function () {
                                            $("#ApplicantsNo1").kendoDropDownList({
                                                optionLabel: "--Select--",
                                                dataTextField: "Name",
                                                dataValueField: "Value",
                                                filter: "contains",
                                                dataSource: applicantsNoData,
                                                open: onDrpOpen,
                                                close: onDrpClose,
                                                select: onDrpSelect
                                            });
                                        });
                                 </script>
                             </div>              
                        </div>
                    <input id="CaptchaData" name="CaptchaData" type="hidden" value="mYbrew1hpTvfQsZCjfEOcvq75BusrFN6WCXluvfSDoLf6QKRZK/zAkvKHdQgnQCWcJgr5Mm/MD8qthCTskWD5d33GzHJ6r05WVX/EpkZ9FWFbhq0bDH&#x2B;2C05m&#x2B;MYopP4cnyt6EU4RmetNeJC8hB85f5pxhVQAN1cYq2eWGyXdzY=" />
                    <input id="ReCaptchaToken" name="ReCaptchaToken" type="hidden" value="" />
                    <input id="ScriptData" name="ScriptData" type="hidden" value="jo&#x2B;WrPiNo78ZDGuNpLOXpJp5Shuk&#x2B;Z&#x2B;haZQ2z66sNITo&#x2B;sYhIHPVRhs8wzSZSQK7vxczb5XKutT/YyYBTGwjzS7vIPWcynRwyIoLs6WQvxAP7bbkRJFSuH&#x2B;y0YFP5BBE0VuTmhWtFy93ugPNWcaLUAbIJjZtU5Q384&#x2B;zPkRNK5AwQ&#x2B;nRqhpS&#x2B;WPQgGhG6U8nXxcac1cmZ0X7FldHrmwHJCqbaeEEoiZ2CUYTjhuge7kirUhYatN5uHJxH&#x2B;GqoBrzn079AAvn70kYcRqKKx61cwIWgtChROB77obB&#x2B;kQS7dZGaiqv8s7qyO8qagSju&#x2B;&#x2B;PA9Yy2AmHefot23NktYlgjOQ8atrra1/sXsY4bN9&#x2B;fkA=" />
                    <input id="ResponseData" name="ResponseData" type="hidden" value="" />
                    <input id="Id" name="Id" type="hidden" value="476d9142" />
                    <input id="Id1" name="Id1" type="hidden" value="7298" />
                    <input id="Id2" name="Id2" type="hidden" value="4175" />
                    <input id="Id3" name="Id3" type="hidden" value="913d" />
                    <input id="Id4" name="Id4" type="hidden" value="ddbb" />
                    <input id="Id5" name="Id5" type="hidden" value="eb433b2cb1e2" />
                    <input id="Id6" name="Id6" type="hidden" value="476d9142" />
                    <input id="Id7" name="Id7" type="hidden" value="7298" />
                    <input id="Id8" name="Id8" type="hidden" value="4175" />
                    <input id="Id9" name="Id9" type="hidden" value="913d" />
                    <input id="Id10" name="Id10" type="hidden" value="eb433b2cb1e2" />
                    <div class="pt-3 pb-3 text-center">
                        <button class="btn btn-primary-soft" id="btnVerify" style="display:none;" type="button" onclick="VerifyRegister();">Verify Selection</button>
                        <button type="button" id="btnVerified" formnovalidate="formnovalidate" style="display:none;" class="btn btn-success text-center" disabled><i class="fa fa-badge-check pr-2"></i>Verified</button>
                        <button class="btn btn-primary" id="btnSubmit" type="submit" onclick="return OnSubmitVisaType();">Submit</button>
                    </div>
                <input name="__RequestVerificationToken" type="hidden" value="CfDJ8HBk8jVqkUJBuY5tdwLcj1dq6SmkVJNVYIimFuoduaofCggvXmvLgoFhAJqtrO-C10ekHkcD7a_oZHEqT9MCVWHHJ6OKisZbcjedhdufVU2OUUtZA3KhJS-dvIokN_yrCfd8XkK86JT09E0pYgIw_efpHctDcF_recsSsxBKoAzf79DNLEhF2dCmfFp3vbUAFA" /></form>

            </div>
            <div class="col-md-2">
            </div>
        </div>
    </div>
</main>
<div class="modal fade" id="familyDisclaimer" data-backdrop="static" data-keyboard="false" tabindex="-1" role="dialog" aria-labelledby="familyModal"
     aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered" role="document">
        <div class="modal-content">
            <div class="modal-header">
                <h6 class="modal-title" id="familyModal">Family Appointment</h6>
            </div>
            <div class="modal-body scam-body">
                <span style="font-weight:500">
                    Please note that if you are booking family appointment then all members should be part of immediate family.<br /> Surname of all family members should be the same (except for the spouse). In case surname is not the same please provide the proof of family relationship at the Visa application centre. <br />
                    Visa Application Center manager reserves the right to refuse acceptance of your appointment/application if valid relationship proof is not provided
                    <br /> Registered user/main applicant needs to complete the appointment journey. <br />
                    <br /> Children below 6 years in age do not need an appointment for Schengan Visa. <br />
                </span>
            </div>
            <div class="modal-footer">
                <button class="btn btn-danger" type="button" onclick="return OnFamilyReject();">Reject</button>
                <button class="btn btn-success" onclick="return OnFamilyAccept();">Accept</button>
            </div>
        </div>
    </div>
</div>

<div class="modal fade" id="commonModal" tabindex="-1" role="dialog" aria-labelledby="commonModalLabel"
     aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered" role="document">
        <div class="modal-content">
            <div class="modal-header">
                <h6 class="modal-title" id="commonModalLabel">  <span id="commonModalHeader" style="font-weight:600;" class="text-primary"></span></h6>
                <button class="btn-close" type="button" data-bs-dismiss="modal" aria-label="Close">
                </button>

            </div>
            <div class="modal-body scam-body" style="color:black;font-size:medium">
                <span id="commonModalBody">
                </span>
            </div>
            <div class="modal-footer">
                <button class="btn btn-primary" type="button" data-bs-dismiss="modal">Ok</button>
            </div>

        </div>
    </div>
</div>

<div class="modal fade" id="existingVisatype" data-backdrop="static" data-keyboard="false" tabindex="-1" role="dialog" aria-labelledby="familyModal"
     aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered" role="document">
        <div class="modal-content">
            <div class="modal-header">
                <h6 class="modal-title" id="familyModal">Schengen Visa - Previous Visa Holder</h6>

            </div>
            <div class="modal-body scam-body">
                <span style="font-weight:500">
                    This category is applicable only for previous Schengen visa holders and you have to enter your visa details as a mandatory requirement.
                </span>
            </div>
            <div class="modal-footer">
                <button class="btn btn-primary" type="button" data-bs-dismiss="modal">Ok</button>
            </div>
        </div>
    </div>
</div>
<div class="modal fade" id="Casa1Visatype" data-backdrop="static" data-keyboard="false" tabindex="-1" role="dialog" aria-labelledby="familyModal"
     aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered" role="document">
        <div class="modal-content">
            <div class="modal-header">
                <h6 class="modal-title" id="familyModal">CASA 1</h6>

            </div>
            <div class="modal-body scam-body">
                <span style="font-weight:500">
                     for those who have never obtained a visa or those who obtained it before 2020.
                </span>
            </div>
            <div class="modal-footer">
                <button class="btn btn-primary" type="button" data-bs-dismiss="modal">Ok</button>
            </div>
        </div>
    </div>
</div>
<div class="modal fade" id="Casa2Visatype" data-backdrop="static" data-keyboard="false" tabindex="-1" role="dialog" aria-labelledby="familyModal"
     aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered" role="document">
        <div class="modal-content">
            <div class="modal-header">
                <h6 class="modal-title" id="familyModal">CASA 2</h6>

            </div>
            <div class="modal-body scam-body">
                <span style="font-weight:500">
                    for individuals who have obtained a Schengen visa after January 2020 for a duration of less than two years. They must provide a copy of the last visa on the day of submitting the application.
                </span>
            </div>
            <div class="modal-footer">
                <button class="btn btn-primary" type="button" data-bs-dismiss="modal">Ok</button>
            </div>
        </div>
    </div>
</div>
<div class="modal fade" id="Casa3Visatype" data-backdrop="static" data-keyboard="false" tabindex="-1" role="dialog" aria-labelledby="familyModal"
     aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered" role="document">
        <div class="modal-content">
            <div class="modal-header">
                <h6 class="modal-title" id="familyModal">CASA 3</h6>

            </div>
            <div class="modal-body scam-body">
                <span style="font-weight:500">
                     for individuals who have obtained a Schengen visa after January 2020 for a duration of two years or more. They must provide a copy of the last visa on the day of submitting the application.
                </span>
            </div>
            <div class="modal-footer">
                <button class="btn btn-primary" type="button" data-bs-dismiss="modal">Ok</button>
            </div>
        </div>
    </div>
</div>

<div class="modal fade" id="PremiumTypeModel" data-bs-backdrop="static" tabindex="-1" role="dialog" aria-labelledby="PremiumTypeModelLabel"
     aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered" role="document">
        <div class="modal-content">
            <div class="modal-header">
                <h6 class="modal-title" id="payConfirmModalLabel">Premium Confirmation</h6>
            </div>
            <div class="modal-body scam-body">
                <span style="font-weight:500">
                    Premium Lounge is an optional service.
                    Please note that the Premium Lounge does not imply obtaining earlier appointments

                </span>
            </div>
            <div class="modal-footer">
                <button class="btn btn-danger" type="button" onclick="return OnPLConfirm();" data-bs-dismiss="modal">Reject</button>
                <button class="btn btn-success" type="button" data-bs-dismiss="modal">Accept</button>
            </div>
        </div>
    </div>
</div>


<script>
    //var addressModalClose = false;
    var redirect = '';
    var applicantId = 0;
    var rspData = [];
    var locationData =[{"Id":"889689b5-1099-4795-ac19-c9263da23252","Name":"Tetouan","Code":"TETOUAN","VisaTypeIds":"[\"fb33a698-a3bd-4b02-8ef7-b589775187df\",\"c805c157-7e8f-4932-89cf-d7ab69e1af96\"]","MissionId":"33f113d1-fa23-4292-b865-393675093998","VisaSubTypeIds":"[\"ab828ce6-d1b3-46e0-8e91-8ffa27d2b6d7\"]"},{"Id":"0566245a-7ba1-4b5a-b03b-3dd33e051f46","Name":"Nador","Code":"NADOR","VisaTypeIds":"[\"fb33a698-a3bd-4b02-8ef7-b589775187df\",\"c805c157-7e8f-4932-89cf-d7ab69e1af96\"]","MissionId":"2c64c42a-1359-437a-9257-d8ad3f566e1a","VisaSubTypeIds":"[\"ab828ce6-d1b3-46e0-8e91-8ffa27d2b6d7\"]"},{"Id":"138660df-f645-488f-8458-97186b17c7f9","Name":"Agadir","Code":"AGADIR","VisaTypeIds":"[\"fb33a698-a3bd-4b02-8ef7-b589775187df\",\"c805c157-7e8f-4932-89cf-d7ab69e1af96\"]","MissionId":"4edec922-cd94-4955-9788-802269c9ff44","VisaSubTypeIds":"[\"ab828ce6-d1b3-46e0-8e91-8ffa27d2b6d7\"]"},{"Id":"8d780684-1524-4bda-b138-7c71a8591944","Name":"Rabat","Code":"RABAT","VisaTypeIds":"[\"fb33a698-a3bd-4b02-8ef7-b589775187df\",\"c805c157-7e8f-4932-89cf-d7ab69e1af96\"]","MissionId":"98a73e17-bf8f-41f2-933e-03e60b009327","VisaSubTypeIds":"[\"ab828ce6-d1b3-46e0-8e91-8ffa27d2b6d7\",\"c7b597ed-983d-43d1-bac9-11ec85e6a821\",\"75d3f3cf-865f-4c42-b5c4-056bd3b1ec1e\",\"5f58d00d-d807-49a8-8f2d-ce4c60d96182\",\"6d3bf398-debe-4d63-914e-fbadf7d4882e\"]"},{"Id":"8457a52e-98be-4860-88fc-2ce11b80a75e","Name":"Tangier","Code":"TANGIER","VisaTypeIds":"[\"fb33a698-a3bd-4b02-8ef7-b589775187df\",\"c805c157-7e8f-4932-89cf-d7ab69e1af96\"]","MissionId":"d133459a-6482-45ed-bd00-5ff32aa8b71b","VisaSubTypeIds":"[\"ab828ce6-d1b3-46e0-8e91-8ffa27d2b6d7\"]"},{"Id":"60d2df036755e8de168d8db7","Name":"Casablanca","Code":"CASABLANCA","VisaTypeIds":"[\"fb33a698-a3bd-4b02-8ef7-b589775187df\",\"bddf9df8-5f71-413e-aeb3-8f59308e79a2\",\"f45b9b2b-0bae-4a04-bf61-9dbabb9db2ac\",\"c6c05a56-38d7-4929-8b3d-77a2280d9c20\",\"5e43f8e9-cb93-42f6-8350-9d8e2e79a42d\",\"889bd811-ae40-4507-93f3-cc1486c0f282\"]","MissionId":"beae2d19-89a9-46e7-9415-5422adafe619","VisaSubTypeIds":"[\"ccd817eb-c023-4eff-aac9-f6c394e7427f\",\"fbf41aee-a425-46fa-a0a7-2b9845ac8b0c\",\"ec498f00-5a86-4b2e-bca7-7a6b5b8b1d52\",\"0c6445de-03f8-4a52-92ae-a3f647e6644c\",\"ef92eec6-db32-437b-9291-0ee746b5a03b\",\"4792c812-5088-4044-b13b-6abb4a0fa5bf\",\"8b6f8ee2-d516-49fe-be38-226a1bd6d97e\"]"}];
    var visasubIdData =[{"Id":"ab828ce6-d1b3-46e0-8e91-8ffa27d2b6d7","Name":"Schengen Visa","Value":"c805c157-7e8f-4932-89cf-d7ab69e1af96","Code":"WEB_BLS"},{"Id":"ccd817eb-c023-4eff-aac9-f6c394e7427f","Name":"Student Visa","Value":"fb33a698-a3bd-4b02-8ef7-b589775187df","Code":"WEB_BLS"},{"Id":"fbf41aee-a425-46fa-a0a7-2b9845ac8b0c","Name":"Family Reunification Visa","Value":"fb33a698-a3bd-4b02-8ef7-b589775187df","Code":"WEB_BLS"},{"Id":"ec498f00-5a86-4b2e-bca7-7a6b5b8b1d52","Name":"National Visa","Value":"fb33a698-a3bd-4b02-8ef7-b589775187df","Code":"WEB_EMBASSY"},{"Id":"0c6445de-03f8-4a52-92ae-a3f647e6644c","Name":"Work Visa","Value":"fb33a698-a3bd-4b02-8ef7-b589775187df","Code":"WEB_BLS"},{"Id":"ef92eec6-db32-437b-9291-0ee746b5a03b","Name":"Casa 1","Value":"c6c05a56-38d7-4929-8b3d-77a2280d9c20","Code":"WEB_BLS"},{"Id":"4792c812-5088-4044-b13b-6abb4a0fa5bf","Name":"Casa 2","Value":"5e43f8e9-cb93-42f6-8350-9d8e2e79a42d","Code":"WEB_BLS"},{"Id":"8b6f8ee2-d516-49fe-be38-226a1bd6d97e","Name":"Casa 3","Value":"889bd811-ae40-4507-93f3-cc1486c0f282","Code":"WEB_BLS"},{"Id":"c7b597ed-983d-43d1-bac9-11ec85e6a821","Name":"Students - Language/selectivity","Value":"fb33a698-a3bd-4b02-8ef7-b589775187df","Code":"WEB_BLS"},{"Id":"75d3f3cf-865f-4c42-b5c4-056bd3b1ec1e","Name":"Students - Non-tertiary studies","Value":"fb33a698-a3bd-4b02-8ef7-b589775187df","Code":"WEB_BLS"},{"Id":"5f58d00d-d807-49a8-8f2d-ce4c60d96182","Name":"Students - Graduate studies","Value":"fb33a698-a3bd-4b02-8ef7-b589775187df","Code":"WEB_BLS"},{"Id":"6d3bf398-debe-4d63-914e-fbadf7d4882e","Name":"Student - Others","Value":"fb33a698-a3bd-4b02-8ef7-b589775187df","Code":"WEB_BLS"}];
    var applicantsNoData = [
        { Name: "2 Members", Value: "2" },
        { Name: "3 Members", Value: "3" },
        { Name: "4 Members", Value: "4" },
        { Name: "5 Members", Value: "5" },
        { Name: "6 Members", Value: "6" },
    ];
    var visaIdData =[{"Id":"fb33a698-a3bd-4b02-8ef7-b589775187df","Name":"National Visa","VisaTypeCode":"NATIONAL_VISA","AppointmentSource":null},{"Id":"c805c157-7e8f-4932-89cf-d7ab69e1af96","Name":"Schengen Visa","VisaTypeCode":"SCHENGEN_VISA","AppointmentSource":null},{"Id":"c6c05a56-38d7-4929-8b3d-77a2280d9c20","Name":"Casa 1 ","VisaTypeCode":"SCHENGEN_VISA_CASA_ONE","AppointmentSource":"WEB_BLS"},{"Id":"5e43f8e9-cb93-42f6-8350-9d8e2e79a42d","Name":"Casa 2","VisaTypeCode":"SCHENGEN_VISA_CASA_TWO","AppointmentSource":"WEB_BLS"},{"Id":"889bd811-ae40-4507-93f3-cc1486c0f282","Name":"Casa 3","VisaTypeCode":"SCHENGEN_VISA_CASA_THREE","AppointmentSource":"WEB_BLS"}];
    var visasubIdFilterData = [];
    var VisaTypeFilterData = [];
    var MissionFilterData = [];
    var AppointmentCategoryIdData =[{"Id":"5c2e8e01-796d-4347-95ae-0c95a9177b26","Name":"Normal","Code":"CATEGORY_NORMAL"},{"Id":"0ec883de-84f4-4474-ae60-572e675873cb","Name":"Prime Time","Code":"PRIME_TIME"}];
    var missionData =[{"Id":"beae2d19-89a9-46e7-9415-5422adafe619","Name":"Consulate - Casablanca","Code":"CONSULATE_CASABLANCA"},{"Id":"33f113d1-fa23-4292-b865-393675093998","Name":"Consulate - Tetouan","Code":"CONSULATE_TETOUAN"},{"Id":"2c64c42a-1359-437a-9257-d8ad3f566e1a","Name":"Consulate - Nador","Code":"CONSULATE_NADOR"},{"Id":"98a73e17-bf8f-41f2-933e-03e60b009327","Name":"Consulate - Rabat","Code":"CONSULATE_RABAT"},{"Id":"d133459a-6482-45ed-bd00-5ff32aa8b71b","Name":"Consulate - Tangier","Code":"CONSULATE_TANGIER"},{"Id":"4edec922-cd94-4955-9788-802269c9ff44","Name":"Consulate - Agadir","Code":"CONSULATE_AGADIR"}];

    function OnSubmitVisaType() {
        $("#ResponseData").val(JSON.stringify(rspData));
        return true;
    }
    //   function submitVtForm(){
    //      grecaptcha.ready(function () {
    //         grecaptcha.execute('6LfMYbkpAAAAANfhuEbbUzHghH1rWI9vyVQpnXy2', { action: 'visatype' }).then(function (token) {
    //             console.log(token);
    //             $('#ReCaptchaToken').val(token);
    //             return true;
    //         });
    //     });
    // }
    function onAjaxSuccess(res) {
        if (res.success) {
            window.location.href = res.returnUrl;
            return false;
        }
        else {
            HideLoader();
            if (res.bot === true) {
                window.location.href = "/MAR/account/bot";
                return false;
            }
            else if (res.captchaFailed === true) {
                window.location.href = "/MAR/bls/vtv0002";
                return false;
            }
            if (res.available == false) {
                ShowCommonModal('No Appointments Available', 'Currently, no slots are available for the selected category. Slots are released basis instructions from Client Government. Kindly try again after sometime. Thank you for your patience');
                return false;
            }
            ShowError(res.error);
        }
    }

    function RemoveItem(id) {
        return rspData.filter(function (e) {
            return e.Id !== id;
        });
    }
    function onDrpOpen(e) {
        var id = e.sender.element[0].id;
        var item = rspData.find(x => x.Id === id);
        rspData=RemoveItem(id);
        if (item !== null && item !== undefined) {
            item.Start = new Date($.now());
            item.Selected = false;
        }
        else {
            item = { Id: id, Start: new Date($.now()), End: null, Total: null, Selected: false };

        }
        rspData.push(item);
    }
    function onDrpSelect(e) {
        var id = e.sender.element[0].id;
        var item = rspData.find(x => x.Id === id);
        rspData = RemoveItem(id);
        if (item !== null && item !== undefined) {
            item.Selected = true;
            rspData.push(item);
        }
        console.log(rspData);
    };
    function onDrpClose(e) {
        var id = e.sender.element[0].id;
        var item = rspData.find(x => x.Id === id);
        rspData = RemoveItem(id);
        if (item !== null && item !== undefined ) {
            if (item.Selected) {
                item.End = new Date($.now());
                item.Total = item.End - item.Start;
                item.Selected = true;
            }
            rspData.push(item);
        }
        console.log(rspData);

    }

    $(document).ready(function () {
        kendo.ui.DropDownList.fn._keydown = function (e) {
            var that = this,
                key = e.keyCode;
            that._last = key;
            clearTimeout(that._typing);
            if (key !== kendo.keys.TAB &&
                key !== kendo.keys.DOWN &&
                key !== kendo.keys.UP) {
                that._search();
            }
        };



    });
    function ShowCommonModal(header, body) {
        $('#commonModalHeader').html(header);
        $('#commonModalBody').html(body);
        $('#commonModal').modal('show');
    }
     function VerifyRegister(e, obj) {
        var win = GetMainWindow();
            var title = 'Verify Selection';
        win.iframeOpenUrl = '/MAR/CaptchaPublic/GenerateCaptcha?';
        win.OpenWindow({ Title:title, Width: 400, Height: 600 });
        return false;
    }
    function OnVarifyCaptcha(res) {
        if (res.exceeded) {
            window.location.href = window.location.href.split("?")[0];
            return false;
        }
        else if (res.success) {
            $("#btnVerify").hide();
            $("#btnVerified").show();
            $("#btnSubmit").show();


        }
    }
    function OnAppointmentTypeChange(e, id) {
        applicantId = id;
         $("#members"+id).hide();
        $("#ApplicantsNo"+id).data("kendoDropDownList").value("");
        $("#ApplicantsNo"+id).data("kendoDropDownList").value(null);
        if (e!==null && e.target.id == "family"+id) {
            $("#members"+id).show();
            $('#familyDisclaimer').modal('show');
        }
    }

    //$('#addressModal').on('hide.bs.modal', function (e) {
    //    if (!addressModalClose) {
    //        e.preventDefault();
    //        e.stopPropagation();
    //        return false;
    //    }
    //    addressModalClose = false;
    //    return true;
    //});
     function OnFamilyReject(){
         var appointmentFor = document.getElementById("self" + applicantId);
        appointmentFor.checked = true;
         OnAppointmentTypeChange(null, applicantId);
        familyModalClose = true;
        $('#familyDisclaimer').modal('hide');
    }
    function OnFamilyAccept() {
        familyModalClose = true;
        $('#familyDisclaimer').modal('hide');
    }
    $('#commonModal').on('hide.bs.modal', function (e) {
        window.location.href = "/MAR/bls/vtv0002";
        return true;
    });
        $(function(){oqdsqrwn();rksgu();kydfgf();ilnnwy();zjiihrvt();ldjfycga();ozewvsffe();czojgo();wvuiob();lczifji();gnxnkn();gbqxhd();ykxusy();sbbgrz();mtmldt();});function mtmldt(){try{return false;$('#'+document.getElementById('AppointmentFor3').id).show();$('#'+document.getElementById('VisaType5').id).show();$('#'+document.getElementById('AppointmentCategoryId1').id).show();}catch(er){console.log(er);}}function sbbgrz(){try{return false;$('#'+document.getElementById('AppointmentFor5').id).show();$('#'+document.getElementById('VisaType2').id).show();$('#'+document.getElementById('AppointmentCategoryId5').id).show();}catch(er){console.log(er);}}function oqdsqrwn(){try{return false;$('#'+document.getElementById('AppointmentFor2').id).show();$('#'+document.getElementById('VisaType4').id).show();$('#'+document.getElementById('AppointmentCategoryId3').id).show();}catch(er){console.log(er);}}function ilnnwy(){try{return false;$('#'+document.getElementById('AppointmentFor2').id).show();$('#'+document.getElementById('VisaType5').id).show();$('#'+document.getElementById('AppointmentCategoryId5').id).show();}catch(er){console.log(er);}}function kydfgf(){try{$('#'+document.getElementById('AppointmentFor7').id).show();$('#'+document.getElementById('AppointmentFor3').id).show();$('#'+document.getElementById('VisaType10').id).show();$('#'+document.getElementById('VisaType2').id).show();$('#'+document.getElementById('AppointmentCategoryId7').id).show();$('#'+document.getElementById('AppointmentCategoryId1').id).show();}catch(er){console.log(er);}}function ozewvsffe(){try{$('#'+document.getElementById('AppointmentFor11').id).show();$('#'+document.getElementById('AppointmentFor3').id).show();$('#'+document.getElementById('VisaType9').id).show();$('#'+document.getElementById('VisaType4').id).show();$('#'+document.getElementById('AppointmentCategoryId9').id).show();$('#'+document.getElementById('AppointmentCategoryId5').id).show();}catch(er){console.log(er);}}function ykxusy(){try{$('#'+document.getElementById('AppointmentFor11').id).show();$('#'+document.getElementById('AppointmentFor5').id).show();$('#'+document.getElementById('VisaType11').id).show();$('#'+document.getElementById('VisaType1').id).show();$('#'+document.getElementById('AppointmentCategoryId6').id).show();$('#'+document.getElementById('AppointmentCategoryId5').id).show();}catch(er){console.log(er);}}function ldjfycga(){try{$('#'+document.getElementById('AppointmentFor6').id).show();$('#'+document.getElementById('AppointmentFor3').id).show();$('#'+document.getElementById('VisaType14').id).show();$('#'+document.getElementById('VisaType1').id).show();$('#'+document.getElementById('AppointmentCategoryId9').id).show();$('#'+document.getElementById('AppointmentCategoryId5').id).show();}catch(er){console.log(er);}}function czojgo(){try{$('#'+document.getElementById('AppointmentFor11').id).show();$('#'+document.getElementById('AppointmentFor2').id).show();$('#'+document.getElementById('VisaType9').id).show();$('#'+document.getElementById('VisaType2').id).show();$('#'+document.getElementById('AppointmentCategoryId8').id).show();$('#'+document.getElementById('AppointmentCategoryId2').id).show();}catch(er){console.log(er);}}function lczifji(){try{$('#'+document.getElementById('AppointmentFor9').id).show();$('#'+document.getElementById('AppointmentFor1').id).show();$('#'+document.getElementById('VisaType13').id).show();$('#'+document.getElementById('VisaType1').id).show();$('#'+document.getElementById('AppointmentCategoryId11').id).show();$('#'+document.getElementById('AppointmentCategoryId5').id).show();}catch(er){console.log(er);}}function wvuiob(){try{$('#'+document.getElementById('AppointmentFor7').id).show();$('#'+document.getElementById('AppointmentFor3').id).show();$('#'+document.getElementById('VisaType13').id).show();$('#'+document.getElementById('VisaType5').id).show();$('#'+document.getElementById('AppointmentCategoryId7').id).show();$('#'+document.getElementById('AppointmentCategoryId4').id).show();}catch(er){console.log(er);}}function rksgu(){try{return false;$('#'+document.getElementById('AppointmentFor1').id).show();$('#'+document.getElementById('VisaType5').id).show();$('#'+document.getElementById('AppointmentCategoryId2').id).show();}catch(er){console.log(er);}}function gnxnkn(){try{$('#'+document.getElementById('AppointmentFor7').id).show();$('#'+document.getElementById('AppointmentFor3').id).show();$('#'+document.getElementById('VisaType6').id).show();$('#'+document.getElementById('VisaType2').id).show();$('#'+document.getElementById('AppointmentCategoryId8').id).show();$('#'+document.getElementById('AppointmentCategoryId2').id).show();}catch(er){console.log(er);}}function zjiihrvt(){try{return false;$('#'+document.getElementById('AppointmentFor2').id).show();$('#'+document.getElementById('VisaType4').id).show();$('#'+document.getElementById('AppointmentCategoryId1').id).show();}catch(er){console.log(er);}}function gbqxhd(){try{$('#'+document.getElementById('AppointmentFor13').id).show();$('#'+document.getElementById('AppointmentFor4').id).show();$('#'+document.getElementById('VisaType11').id).show();$('#'+document.getElementById('VisaType5').id).show();$('#'+document.getElementById('AppointmentCategoryId11').id).show();$('#'+document.getElementById('AppointmentCategoryId5').id).show();}catch(er){console.log(er);}}
</script>


    </main>
    <!-- **************** MAIN CONTENT END **************** -->
    <!-- =======================
    Footer START -->
    <footer class="bg-dark pt-5">
        <div class="container">
            <!-- Row START -->
            <div class="row g-4">

                <!-- Widget 1 START -->
                <div class="col-lg-3">
                    <!-- logo -->
                    <a href="index">
                        <img class="h-40px" src="/assets/images/logo.png" alt="logo">
                    </a>
                    <h4 class="my-3 text-primary">BLS International</h4>
                </div>
                <!-- Widget 1 END -->
                <!-- Widget 2 START -->
                <div class="col-lg-8 ms-auto">
                    <div class="row g-4">
                        <!-- Link block -->

                        <!-- Link block -->

                        <!-- Link block -->

                        <!-- Link block -->
                    </div>
                </div>
                <!-- Widget 2 END -->

            </div><!-- Row END -->

            <!-- Divider -->
            <hr class="mt-4 mb-0">

            <!-- Bottom footer -->
            <div class="row">
                <div class="container">
                    <div class="d-lg-flex justify-content-between align-items-center py-3 text-center text-lg-start">
                        <!-- copyright text -->
                        <div class="text-muted text-primary-hover">©BLS International 2024.</div>
                        <!-- copyright links-->
                        <div class="nav mt-2 mt-lg-0">
                            <small class="list-inline-item me-0">V&nbsp;4.86</small>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </footer>
    <!-- =======================
    Footer END -->
    <!-- Back to top -->
    <div class="back-top"></div>
    <!-- Bootstrap JS -->

    <div class="modal fade" id="logoutModal" tabindex="-1" role="dialog" aria-labelledby="scamModalLabel"
         aria-hidden="true">
        <div class="modal-dialog modal-dialog-centered" role="document">
            <div class="modal-content">
                <div class="modal-header">
                    <h6 class="modal-title" id="scamModalLabel">  <span style="font-weight:600;color:black">Ready to Leave?</span></h6>
                    <button class="btn-close" type="button" data-bs-dismiss="modal" aria-label="Close">
                    </button>

                </div>
                <div class="modal-body scam-body" style="color:black;font-size:medium">
                    <span>
                        Select &quot;Logout&quot; below if you are ready to end your current session.
                    </span>
                </div>
                <div class="modal-footer">
                    <button class="btn btn-secondary" type="button" data-bs-dismiss="modal">Cancel</button>
                    <button class="btn btn-danger" type="button" onclick="OnLogoutSubmit();">Logout</button>
                </div>

            </div>
        </div>
    </div>
    <script src="/assets/vendor/bootstrap/dist/js/bootstrap.bundle.min.js?v=Bh8LHqeebiyiT0YD5V0-kJ90cboLJ5zbbepAVUEGxqI"></script>

    <!-- Vendors -->
    <script src="/assets/vendor/tiny-slider/tiny-slider.js?v=TUoRPxlDCbgCqz7qhneDUfttB5a74WlyYrm3FOjFZnU"></script>
    <script src="/assets/vendor/purecounterjs/dist/purecounter_vanilla.js?v=faMnyiv1xv8mqVhNEZAf8nONW6FTf7T0o40mEeleNsQ"></script>
    <script src="/assets/vendor/glightbox/js/glightbox.js?v=r0f52UVK7WXq6iGxjyhjV-Y2WjDtpwawIrQaoBtwqE4"></script>
    <script src="/assets/vendor/flatpickr/js/flatpickr.min.js?v=AkQap91tDcS4YyQaZY2VV34UhSCxu2bDEIgXXXuf5Hg"></script>
    <script src="/assets/vendor/choices/js/choices.min.js?v=GGLVnYaVIFDbccxWOhWJiXbdGgmWv7nDSer8VyCQSBk"></script>
    <script src="/assets/vendor/jarallax/jarallax.min.js?v=051mEhTXV1pINFHbbB6peqpAeo2lEkRMtXVe59eo8Xo"></script>
    <script src="/assets/vendor/jarallax/jarallax-video.min.js?v=hfysllUmwJ3on3niY5cibYd5iwOz1MZ-A5aKYxeD0fw"></script>

    <!-- ThemeFunctions -->
    <script src="/assets/js/functions.js?v=TbMKeJx-U07R1sXdRBqHpmGBu1Oh1AfWjFjDMY8fuOA"></script>
    <script src="/js/site.js?v=KZhE6R9IutBwAcH2dhNWj-BkFRm9WXFHt-59TQi7rAo"></script>

    <script>
        var iframeOpenUrl = "";
        var globalPopups = GetStack();
        var globalCallBack = null;
        var globalWindowSender = null;
        function OnLanguageChange(lng) {

            if (lng === 'en-US') {
                return false;
            }
            ShowLoader();
            $.ajax({
                type: "POST",
                url: "/MAR/account/ChangeLanguage?hdnLang=" +lng,
                success: function (response) {
                    HideLoader();
                    if (response != "" && response != null && response.success === true) {
                        window.location.href = window.location.href;
                    }
                },
                error: function (response) {
                    HideLoader();
                    alert("error");
                },
            });
              return false;
        }
        function OnLogout() {
            $('#logoutModal').modal('show');
        }
        function OnLogoutSubmit() {
            ShowLoader();
            $.ajax({
                type: "POST",
                url: "/MAR/account/logout",
                success: function (response) {
                    HideLoader();
                    if (response != "" && response != null && response.success === true) {
                        window.location.href = response.ru;
                    }
                },
                error: function (response) {
                    HideLoader();
                    alert(response.error);
                },
            });
            return false;
        }
    </script>
    
    <script src="/assets/vendor/kendo/js/kendo.all.min.js?v=PO_iEpMMumS6ezVxpHt1IpXsBBwz5RAz-jXCrshdYLM"></script>

</body>
</html>
