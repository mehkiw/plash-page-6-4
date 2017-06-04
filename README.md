# plash-page-6-4


<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />

    <title>adidas YEEZY POWERPHASE by Kanye West</title>

    <meta name="description" content="The adidas and Kanye West collaboration: be the first to get the new adidas YEEZY POWERPHASE.">

    <link rel="canonical" href="http://adidas.com/yeezy">
    <link rel="image_src" href="/vp_assets/images/powerphase/share-image.jpg">

    <!-- Schema.org -->
    <meta itemprop="name" content="adidas YEEZY POWERPHASE by Kanye West">
    <meta itemprop="description" content="The adidas and Kanye West collaboration: be the first to get the new adidas YEEZY POWERPHASE.">
    <meta itemprop="image" content="/vp_assets/images/powerphase/share-image.jpg">

    <!-- Open Graph -->
    <meta property="fb:app_id" content="159031900855798">
    <meta property="og:site_name" content="adidas">
    <meta property="og:type" content="website">
    <meta property="og:title" content="adidas YEEZY POWERPHASE by Kanye West">
    <meta property="og:description" content="The adidas and Kanye West collaboration: be the first to get the new adidas YEEZY POWERPHASE.">
    <meta property="og:url" content="http://www.adidas.com/yeezy">
    <meta property="og:image" content="/vp_assets/images/powerphase/share-image.jpg">
    <meta property="og:ttl" content="86400">

    <!-- Twitter Card -->
    <meta name="twitter:card" content="summary">
    <meta name="twitter:site" content="@adidas">
    <meta name="twitter:title" content="adidas YEEZY POWERPHASE by Kanye West">
    <meta name="twitter:description" content="The adidas and Kanye West collaboration: be the first to get the new adidas YEEZY POWERPHASE.">
    <meta name="twitter:image" content="/vp_assets/images/powerphase/share-image.jpg">
    <meta name="twitter:url" content="http://www.adidas.com/yeezy">

    <!--Style files -->
    <link href="/vp_assets/css/libraries.min.css?v=19" rel="stylesheet">
    <link href="/vp_assets/css/application.css?v=19" rel="stylesheet">

    <!-- Javascript -->
    <script src="https://www.google.com/recaptcha/api.js"></script>
    <script src="/vp_assets/js/libraries.min.js?v=19"></script>

    <script>

        // Refresh page with set intervals
        setTimeout(function(){window.location.reload(1);}, 60000);

        // Set tracking cookies
        document.cookie="HRPYYU=true";

        // Defaults
        window.DEVICE            = 'mobile';
        window.ENV               = 'PROD';
        window.TRACKING_ENV      = 'prod';
        window.MARKET            = 'US';
        window.LANGUAGE          = 'en_US';
        window.TRACKING_NAME     = 'KANYE YEEZY';
        window.OCAPI_KEY         = '';
        window.LANGUAGE_LOCATION = '/vp_assets/languages/';
        window.ASSET_PATH        = '/vp_assets/_FILE_';
        window.PLACES_API_HOST   = "placesws.adidas-group.com";
        window.STORE_FINDER_TAG  = "";
        window.LANGUAGE_JSON     = "";

        //
        // Get env and load tracking script
        //
        (function(){
            var hostname = location.hostname.toLowerCase();

            if (hostname.indexOf('staging') > -1 )
            {
                ENV = 'QA';
                TRACKING_ENV = 'qa';
            }
            else if (hostname.indexOf('development') > -1 )
            {
                ENV = 'DEV';
                TRACKING_ENV = 'dev';
            }
            else if (hostname.indexOf('adidas-kanye') > -1 )
            {
                ENV = 'LOCAL';
                TRACKING_ENV = 'dev';
            }

            $.getScript('//tags.tiqcdn.com/utag/adidas/adidasglobal/'+TRACKING_ENV+'/utag.sync.js');
        })();

        //
        // Get current date
        //
        function currentDate()
        {
            // Create new date object with current date
            var date = new Date();

            // Get day, month and year
            var day = (date.getDate() < 10) ? '0'+date.getDate() : date.getDate().toString()
            var month = (date.getMonth()+1 < 10) ? '0'+(date.getMonth()+1) : (date.getMonth()+1).toString();
            var year = date.getFullYear().toString();

            // Remove '20' from year, we only want the last
            // 2 digits
            year = year.replace('20', '');

            // Return result
            return day+month+year;
        }

        //
        // Markets
        //
        window.MARKETS = {
            "AE": {
                "name": "United Arab Emirates",
                "market": "AE",
                "locales": ["en_AE"],
                "domain": "mena.adidas.com"
            },
            "AR": {
                "name": "Argentina",
                "market": "AR",
                "locales": ["es_AR"],
                "domain": "adidas.com.ar"
            },
            "AT": {
                "name": "Austria",
                "market": "AT",
                "locales": ["de_AT"],
                "domain": "adidas.at"
            },
            "AU": {
                "name": "Australia",
                "market": "AU",
                "locales": ["en_AU"],
                "domain": "adidas.com.au"
            },
            "BE": {
                "name": "Belgium",
                "market": "BE",
                "locales": ["fr_BE"],
                "domain": "adidas.be"
            },
            "BH": {
                "name": "Bahrain",
                "market": "BH",
                "locales": ["en_BH"],
                "domain": "adidas.com.bh"
            },
            "BR": {
                "name": "Brazil",
                "market": "BR",
                "locales": ["pt_BR"],
                "domain": "adidas.com.br"
            },
            "CA": {
                "name": "Canada",
                "market": "CA",
                "locales": ["en_CA"],
                "domain": "adidas.ca"
            },
            "CF": {
                "name": "Canada-French",
                "market": "CF",
                "locales": ["fr_CA"],
                "domain": "adidas.ca"
            },
            "CH": {
                "name": "Switzerland",
                "market": "CH",
                "locales": ["de_CH", "it_CH", "fr_CH", "en_CH"],
                "domain": "adidas.ch"
            },
            "CL": {
                "name": "Chile",
                "market": "CL",
                "locales": ["es_CL"],
                "domain": "adidas.cl"
            },
            "CN": {
                "name": "China",
                "market": "CN",
                "locales": ["zh_CN"],
                "domain": "adidas.cn"
            },
            "CO": {
                "name": "Colombia",
                "market": "CO",
                "locales": ["es_CO"],
                "domain": "adidas.co"
            },
            "CZ": {
                "name": "Czech Republic",
                "market": "CZ",
                "locales": ["cs_CZ"],
                "domain": "adidas.cz"
            },
            "DE": {
                "name": "Germany",
                "market": "DE",
                "locales": ["de_DE"],
                "domain": "adidas.de"
            },
            "DK": {
                "name": "Denmark",
                "market": "DK",
                "locales": ["da_DK"],
                "domain": "adidas.dk"
            },
            "EE": {
                "name": "Baltics",
                "market": "EE",
                "locales": ["et_EE"],
                "domain": "baltics.adidas.com"
            },
            "ES": {
                "name": "Spain",
                "market": "ES",
                "locales": ["es_ES"],
                "domain": "adidas.es"
            },
            "FI": {
                "name": "Finland",
                "market": "FI",
                "locales": ["fi_FI"],
                "domain": "adidas.fi"
            },
            "FR": {
                "name": "France",
                "market": "FR",
                "locales": ["fr_FR"],
                "domain": "adidas.fr"
            },
            "GB": {
                "name": "United Kingdom",
                "market": "GB",
                "locales": ["en_GB"],
                "domain": "adidas.co.uk"
            },
            "GR": {
                "name": "Greece",
                "market": "GR",
                "locales": ["en_GR"],
                "domain": "adidas.gr"
            },
            "HK": {
                "name": "Hong Kong",
                "market": "HK",
                "locales": ["zh_HK"],
                "domain": "adidas.com.hk"
            },
            "HU": {
                "name": "Hungary",
                "market": "HU",
                "locales": ["hu_HU"],
                "domain": "adidas.hu"
            },
            "ID": {
                "name": "Indonesia",
                "market": "ID",
                "locales": ["id_ID"],
                "domain": "adidas.co.id"
            },
            "IE": {
                "name": "Ireland",
                "market": "IE",
                "locales": ["en_IE"],
                "domain": "adidas.ie"
            },
            "IN": {
                "name": "India",
                "market": "IN",
                "locales": ["en_IN"],
                "domain": "adidas.co.in"
            },
            "IT": {
                "name": "Italy",
                "market": "IT",
                "locales": ["it_IT"],
                "domain": "adidas.it"
            },
            "JP": {
                "name": "Japan",
                "market": "JP",
                "locales": ["ja_JP"],
                "domain": "japan.adidas.com"
            },
            "KR": {
                "name": "Korea",
                "market": "KR",
                "locales": ["ko_KR"],
                "domain": "adidas.co.kr"
            },
            "KW": {
                "name": "Middle-East/North-Africa",
                "market": "KW",
                "locales": ["ar_KW"],
                "domain": "mena.adidas.com"
            },
            "MX": {
                "name": "Mexico",
                "market": "MX",
                "locales": ["es_MX"],
                "domain": "adidas.mx"
            },
            "MY": {
                "name": "Malaysia",
                "market": "MY",
                "locales": ["en_MY"],
                "domain": "adidas.com.my"
            },
            "NG": {
                "name": "Global",
                "market": "NG",
                "locales": ["en_NG"],
                "domain": "global.adidas.com"
            },
            "NL": {
                "name": "Netherlands",
                "market": "NL",
                "locales": ["nl_NL"],
                "domain": "adidas.nl"
            },
            "NO": {
                "name": "Norway",
                "market": "NO",
                "locales": ["en_NO"],
                "domain": "adidas.no"
            },
            "NZ": {
                "name": "New Zealand",
                "market": "NZ",
                "locales": ["en_NZ"],
                "domain": "adidas.co.nz"
            },
            "OM": {
                "name": "Oman",
                "market": "OM",
                "locales": ["en_OM"],
                "domain": "adidas.com.om"
            },
            "PE": {
                "name": "Peru",
                "market": "PE",
                "locales": ["es_PE"],
                "domain": "adidas.pe"
            },
            "PH": {
                "name": "Philippines",
                "market": "PH",
                "locales": ["en_PH"],
                "domain": "adidas.com.ph"
            },
            "PL": {
                "name": "Poland",
                "market": "PL",
                "locales": ["pl_PL"],
                "domain": "adidas.pl"
            },
            "PT": {
                "name": "Portugal",
                "market": "PT",
                "locales": ["pt_PT"],
                "domain": "adidas.pt"
            },
            "QA": {
                "name": "Qatar",
                "market": "QA",
                "locales": ["en_QA"],
                "domain": "adidas.com.qa"
            },
            "RU": {
                "name": "Russia",
                "market": "RU",
                "locales": ["ru_RU"],
                "domain": "adidas.ru"
            },
            "SA": {
                "name": "Saudi Arabia",
                "market": "SA",
                "locales": ["en_SA"],
                "domain": "adidas.com.sa"
            },
            "SE": {
                "name": "Sweden",
                "market": "SE",
                "locales": ["sv_SE"],
                "domain": "adidas.se"
            },
            "SG": {
                "name": "Singapore",
                "market": "SG",
                "locales": ["en_SG"],
                "domain": "adidas.com.sg"
            },
            "SK": {
                "name": "Slovakia",
                "market": "SK",
                "locales": ["sk_SK"],
                "domain": "adidas.sk"
            },
            "TH": {
                "name": "Thailand",
                "market": "TH",
                "locales": ["th_TH"],
                "domain": "adidas.co.th"
            },
            "TR": {
                "name": "Turkey",
                "market": "TR",
                "locales": ["tr_TR"],
                "domain": "adidas.com.tr"
            },
            "TW": {
                "name": "Taiwan",
                "market": "TW",
                "locales": ["zh_TW"],
                "domain": "adidas.com.tw"
            },
            "US": {
                "name": "United States",
                "market": "US",
                "locales": ["en_US"],
                "domain": "adidas.com"
            },
            "VE": {
                "name": "Latin America",
                "market": "VE",
                "locales": ["es_VE"],
                "domain": "latin-america.adidas.com"
            },
            "VN": {
                "name": "Vietnam",
                "market": "VN",
                "locales": ["vi_VN"],
                "domain": "adidas.com.vn"
            },
            "ZA": {
                "name": "South Africa",
                "market": "ZA",
                "locales": ["en_ZA"],
                "domain": "adidas.co.za"
            }
        };

        // Get URL info
        function getUrlInfo()
        {
            var host   = location.host,
                path   = location.pathname,
                result = [];

            result['potentialMarket'] = path.split('/')[1];
            result['domain'] = host.replace('www.', '').replace('staging.', '').replace(/^(m\.|bm\.)/i, '');

            console.log('getUrlInfo', result);

            return result;
        }

        // get CH markets locales in type C format
        function chTypeCUrlMarkets()
        {
            var markets = [], locales, i, l, len;

            locales = MARKETS['CA']['locales'];

            for (i = 0, len = locales.length; i < len; i++) {
                l = locales[i];
                markets[l] = l.replace('_', '-').toLowerCase();
            }

            console.log('chTypeCUrlMarkets', markets);

            return markets;
        }

        // get correct locale for market if it has multiple
        function getCorrectMultiLocale(market, locales)
        {
            var urlInfo, potentialLocale;

            urlInfo = getUrlInfo();
            potentialLocale = urlInfo['potentialMarket'].toLowerCase() + '_' + market;

            if (locales.indexOf(potentialLocale)) {
                console.log('getCorrectMultiLocale', 1, potentialLocale);
                return potentialLocale;
            }

            if (!chTypeCUrlMarkets().indexOf(urlInfo['potentialMarket'])) {
                locales.forEach(function(identifier, locale) {
                    if (identifier === urlInfo['potentialMarket']) {
                        console.log('getCorrectMultiLocale', 2, locale);
                        return locale;
                    }
                });
            }

            console.log('getCorrectMultiLocale', 3, locales[0]);
            return locales[0]; // Fallback is to return first locale
        }

        // Get market
        function getMarket()
        {
            var urlInfo, market;

            urlInfo = getUrlInfo();

            if (urlInfo['domain'] == 'adidas-yeezy.local' || urlInfo['domain'] == 'adidas-kanye.local') {
                console.log('getMarket', 1, MARKET);
                return MARKET;
            }

            // Canadian (CA) multi market workaround
            if (urlInfo['domain'] === MARKETS['CA']['domain']) {
                if (urlInfo['potentialMarket'].toLowerCase() === 'fr') {
                    console.log('getMarket', 2, 'CF');
                    return 'CF';
                } else {
                    console.log('getMarket', 3, 'CA');
                    return 'CA';
                }
            }

            // Switzerland (CH) multi market workaround
            if (!chTypeCUrlMarkets().indexOf(urlInfo['potentialMarket'])) {
                console.log('getMarket', 4, urlInfo['potentialMarket'].split('-')[1]);
                return urlInfo['potentialMarket'].split('-')[1];
            }

            // Check if market exists in url path, eg /de/apps/...
            if (typeof MARKETS[urlInfo['potentialMarket'].toUpperCase()] != 'undefined'
                && urlInfo['domain'] != MARKETS['CH']['domain']
            ) {
                console.log('getMarket', 5, urlInfo['potentialMarket'].toUpperCase());
                return urlInfo['potentialMarket'].toUpperCase();
            }

            market = urlInfo['domain'].match(/.([\w]{2,3})$/)[1].toUpperCase();

            if (market === 'COM' || market === null) {
                console.log('getMarket', 6, MARKET);
                return MARKET;
            }

            return market;
        }

        // get locale
        function getLocale()
        {
            var market, locales;

            market = getMarket();
            locales = MARKETS[market]['locales']

            if (locales.length === 1) {
                console.log('getLocale', 1, locales[0]);
                return locales[0];
            } else {
                console.log('getLocale', 2, getCorrectMultiLocale(market, locales));
                return getCorrectMultiLocale(market, locales);
            }

        }

        //
        // Set market and locale (language)
        //
        (function(){
            var market = getMarket();
            var locale = getLocale();

            MARKET = (null != market) ? market : MARKET;
            LANGUAGE = (null != locale) ? locale : LANGUAGE;
        })();

        //
        // Detect device type
        //
        DEVICE = MobileEsp.DetectTierIphone() ? 'mobile' : 'desktop';
        console.log(LANGUAGE, LANGUAGE.split('_')[0].toUpperCase());

        //
        // Tracking
        //
        var utag_data = {
            campaign_name: TRACKING_NAME,
            country: MARKET,
            date: currentDate(), // Date in users browser
            environment: ENV,
            is_mobile: (DEVICE === 'mobile') ? 'TRUE' : '',
            language: LANGUAGE.split('_')[0].toUpperCase(),
            page_category: "ORIGINALS",
            page_name: "WAITING",
            page_type: "MICROSITE",
            product_sport: "ORIGINALS",
            site_name: "ADIDAS",
            site_owner: "BRAND"
        };

        (function(a,b,c,d){
            a='//tags.tiqcdn.com/utag/adidas/adidasglobal/'+TRACKING_ENV+'/utag.js';
            b=document;
            c='script';
            d=b.createElement(c);
            d.src=a;
            d.type='text/java'+c;
            d.async=true;
            a=b.getElementsByTagName(c)[0];
            a.parentNode.insertBefore(d,a);
        })();
    </script>

    <script src="/vp_assets/js/application.js?v=19"></script>

    <!-- Fonts -->
    <style>
        @font-face {
            font-family: 'YeezyzTStar';
            src: url('/vp_assets/fonts/yeezy_tstar-regular-webfont.eot');
            src: local('☺'), url('/vp_assets/fonts/yeezy_tstar-regular-webfont.woff') format('woff'), url('/vp_assets/fonts/yeezy_tstar-regular-webfont.ttf') format('truetype');
            font-weight: normal;
            font-style: normal;
        }

        @font-face {
            font-family: 'YeezyzTStar';
            src: url('/vp_assets/fonts/yeezy_tstar-bold-webfont.eot');
            src: local('☺'), url('/vp_assets/fonts/yeezy_tstar-bold-webfont.woff') format('woff'), url('/vp_assets/fonts/yeezy_tstar-bold-webfont.ttf') format('truetype');
            font-weight: bold;
            font-style: normal;
        }

        @font-face {
            font-family: 'YeezyzTStar';
            src: url('/vp_assets/fonts/yeezy_tstar-light-webfont.eot');
            src: local('☺'), url('/vp_assets/fonts/yeezy_tstar-light-webfont.woff') format('woff'), url('/vp_assets/fonts/yeezy_tstar-light-webfont.ttf') format('truetype');
            font-weight: 200;
            font-style: normal;
        }

        @font-face {
            font-family: 'YeezyzTStar';
            src: url('/vp_assets/fonts/yeezy_tstar-heavy-webfont.eot');
            src: local('☺'), url('/vp_assets/fonts/yeezy_tstar-heavy-webfont.woff') format('woff'), url('/vp_assets/fonts/yeezy_tstar-heavy-webfont.ttf') format('truetype');
            font-weight: 600;
            font-style: normal;
        }

        @font-face {
            font-family: 'adineueBold';
            src: url('/vp_assets/fonts/adineuePROCyr-Bold.eot');
            src: local('☺'), url('/vp_assets/fonts/adineuePROCyr-Bold.woff') format('woff'), url('/vp_assets/fonts/adineuePROCyr-Bold.ttf') format('truetype');
            font-weight: bold;
            font-style: normal;
        }

        @font-face {
            font-family: 'adineueRegular';
            src: url('/vp_assets/fonts/adineuePROCyr-Regular.eot');
            src: local('☺'), url('/vp_assets/fonts/adineuePROCyr-Regular.woff ') format('woff'), url('/vp_assets/fonts/adineuePROCyr-Regular.ttf') format('truetype');
            font-weight: normal;
            font-style: normal;
        }

        @font-face {
            font-family: 'adineuePROBlack';
            src: url('/vp_assets/fonts/adineuePRO-BlackWeb.eot');
            src: local('☺'), url('/vp_assets/fonts/adineuePRO-BlackWeb.woff') format('woff'), url('/vp_assets/fonts/adineuePRO-BlackWeb.ttf') format('truetype');
            font-weight: bold;
            font-style: normal;
        }

        @font-face {
            font-family: 'icomoon';
            src: url('/vp_assets/fonts/icomoon.eot');
            src: local('☺'), url('/vp_assets/fonts/icomoon.woff') format('woff'), url('/vp_assets/fonts/icomoon.ttf') format('truetype');
            font-weight: normal;
            font-style: normal;
        }

        .sk-fading-circle {
            width: 40px;
            height: 40px;
            position: relative;
        }
        .sk-fading-circle .sk-circle {
            width: 100%;
            height: 100%;
            position: absolute;
            left: 0;
            top: 0;
        }
        .sk-fading-circle .sk-circle:before {
            content: '';
            display: block;
            margin: 0 auto;
            width: 15%;
            height: 15%;
            background-color: #464646;
            border-radius: 100%;
            -webkit-animation: sk-circleFadeDelay 1.2s infinite ease-in-out both;
            animation: sk-circleFadeDelay 1.2s infinite ease-in-out both;
        }
        .sk-fading-circle .sk-circle2 {
            -webkit-transform: rotate(30deg);
            -ms-transform: rotate(30deg);
            transform: rotate(30deg);
        }
        .sk-fading-circle .sk-circle3 {
            -webkit-transform: rotate(60deg);
            -ms-transform: rotate(60deg);
            transform: rotate(60deg);
        }
        .sk-fading-circle .sk-circle4 {
            -webkit-transform: rotate(90deg);
            -ms-transform: rotate(90deg);
            transform: rotate(90deg);
        }
        .sk-fading-circle .sk-circle5 {
            -webkit-transform: rotate(120deg);
            -ms-transform: rotate(120deg);
            transform: rotate(120deg);
        }
        .sk-fading-circle .sk-circle6 {
            -webkit-transform: rotate(150deg);
            -ms-transform: rotate(150deg);
            transform: rotate(150deg);
        }
        .sk-fading-circle .sk-circle7 {
            -webkit-transform: rotate(180deg);
            -ms-transform: rotate(180deg);
            transform: rotate(180deg);
        }
        .sk-fading-circle .sk-circle8 {
            -webkit-transform: rotate(210deg);
            -ms-transform: rotate(210deg);
            transform: rotate(210deg);
        }
        .sk-fading-circle .sk-circle9 {
            -webkit-transform: rotate(240deg);
            -ms-transform: rotate(240deg);
            transform: rotate(240deg);
        }
        .sk-fading-circle .sk-circle10 {
            -webkit-transform: rotate(270deg);
            -ms-transform: rotate(270deg);
            transform: rotate(270deg);
        }
        .sk-fading-circle .sk-circle11 {
            -webkit-transform: rotate(300deg);
            -ms-transform: rotate(300deg);
            transform: rotate(300deg);
        }
        .sk-fading-circle .sk-circle12 {
            -webkit-transform: rotate(330deg);
            -ms-transform: rotate(330deg);
            transform: rotate(330deg);
        }
        .sk-fading-circle .sk-circle2:before {
            -webkit-animation-delay: -1.1s;
            animation-delay: -1.1s;
        }
        .sk-fading-circle .sk-circle3:before {
            -webkit-animation-delay: -1s;
            animation-delay: -1s;
        }
        .sk-fading-circle .sk-circle4:before {
            -webkit-animation-delay: -0.9s;
            animation-delay: -0.9s;
        }
        .sk-fading-circle .sk-circle5:before {
            -webkit-animation-delay: -0.8s;
            animation-delay: -0.8s;
        }
        .sk-fading-circle .sk-circle6:before {
            -webkit-animation-delay: -0.7s;
            animation-delay: -0.7s;
        }
        .sk-fading-circle .sk-circle7:before {
            -webkit-animation-delay: -0.6s;
            animation-delay: -0.6s;
        }
        .sk-fading-circle .sk-circle8:before {
            -webkit-animation-delay: -0.5s;
            animation-delay: -0.5s;
        }
        .sk-fading-circle .sk-circle9:before {
            -webkit-animation-delay: -0.4s;
            animation-delay: -0.4s;
        }
        .sk-fading-circle .sk-circle10:before {
            -webkit-animation-delay: -0.3s;
            animation-delay: -0.3s;
        }
        .sk-fading-circle .sk-circle11:before {
            -webkit-animation-delay: -0.2s;
            animation-delay: -0.2s;
        }
        .sk-fading-circle .sk-circle12:before {
            -webkit-animation-delay: -0.1s;
            animation-delay: -0.1s;
        }

        @-webkit-keyframes sk-circleFadeDelay {
            0%, 39%, 100% { opacity: 0; }
            40% { opacity: 1; }
        }

        @keyframes sk-circleFadeDelay {
            0%, 39%, 100% { opacity: 0; }
            40% { opacity: 1; }
        }

        .mx-legal {
            font-size: 16px
        }

    </style>
</head>
<body class="custom-c in-line">

    <!-- CONTENT START -->
    <div class="kw in-line">

        <!-- HEADER START -->
        <header class="top">

            <div class="inner">
                <figure class="logo">
                    <a href="//www.adidas.com" target="_blank" data-url="home">
                        adidas
                    </a>
                </figure>

                <nav class="menu hidden">
                    <ul class="menu-items">
                        <li class="item men">
                            <a href="#" data-url="men" data-lang="header_men_name">men</a>
                        </li>
                        <li class="item women">
                            <a href="#" data-url="women" data-lang="header_women_name">women</a>
                        </li>
                        <li class="item kids">
                            <a href="#" data-url="kids" data-lang="header_kids_name">kids</a>
                        </li>
                    </ul>
                </nav>

                <aside class="ecom">
                    <ul class="ecom-items">
                        <li class="item my-account">
                            <a href="#" data-url="my_account" alt="My Account">&nbsp;</a>
                        </li>
                        <li class="item cart">
                            <a href="#" data-url="cart" alt="Cart">&nbsp;</a>
                        </li>
                    </ul>
                </aside>
            </div>

        </header>
        <!-- HEADER END -->

        <section id="logo" class="section">

            <div class="inner">
                <div class="spinner">
                    <img src="/vp_assets/images/ajax-loader.gif" style="display:none;">
                    <div class="sk-fading-circle">
                        <div class="sk-circle1 sk-circle"></div>
                        <div class="sk-circle2 sk-circle"></div>
                        <div class="sk-circle3 sk-circle"></div>
                        <div class="sk-circle4 sk-circle"></div>
                        <div class="sk-circle5 sk-circle"></div>
                        <div class="sk-circle6 sk-circle"></div>
                        <div class="sk-circle7 sk-circle"></div>
                        <div class="sk-circle8 sk-circle"></div>
                        <div class="sk-circle9 sk-circle"></div>
                        <div class="sk-circle10 sk-circle"></div>
                        <div class="sk-circle11 sk-circle"></div>
                        <div class="sk-circle12 sk-circle"></div>
                    </div>
                </div>

                <h3 class="title" data-lang="in_line_title">WE ARE LAUNCHING YEEZY POWERPHASE!<br/>YOU ARE NOW IN OUR WAITING ROOM TO BUY YEEZY POWERPHASE. PLEASE DO NOT REFRESH THIS PAGE</h3>
                <p class="message message-1 hidden" data-lang="in_line_message">TO MAKE THE YEEZY POWERPHASE RELEASE AS FAIR AS POSSIBLE WE WILL RANDOMLY ALLOW PEOPLE ACCESS TO OUR SITE. WHEN YOU LAND ON THE PRODUCT PAGE YOU CAN CHECK SIZE AVAILABILITY, SELECT A SIZE AND START FINALIZING YOUR PURCHASE.<br/>PLEASE BE AWARE THAT YOUR PURCHASE WILL ONLY BE FINALE WHEN YOU HAVE FULLY COMPLETED PAYMENT AND RECEIVED AN ORDER SHIPPED EMAIL.</p>
                <p class="message message-2 hidden" data-lang="in_line_message_2">THERE ARE STILL SOME YEEZY POWERPHASE LEFT. PLEASE WAIT AND DO NOT REFRESH THIS PAGE. WHEN YOU GET ON THE PRODUCT PAGE YOU CAN CHECK SIZE AVAILABILITY, SELECT A SIZE AND START FINALIZING YOUR PURCHASE.<br/>PLEASE BE AWARE THAT YOUR PURCHASE WILL ONLY BE FINAL WHEN YOU HAVE FULLY COMPLETED PAYMENT AND RECEIVED AN ORDER SHIPPED EMAIL.</p>
                <p class="message message-3 hidden" data-lang="in_line_message_3">WE STILL HAVE SOME YEEZY POWERPHASE IN STOCK SO DON'T GO AWAY JUST YET! WHEN YOU LAND ON THE PRODUCT PAGE YOU CAN CHECK SIZE AVAILABILITY, SELECT A SIZE AND START FINALIZING YOUR PURCHASE.<br/>PLEASE BE AWARE THAT YOUR PURCHASE WILL ONLY BE FINAL WHEN YOU HAVE FULLY COMPLETED PAYMENT AND RECEIVED AN ORDER SHIPPED EMAIL.</p>
            </div>

        </section>

        <section class="gallery-cart-wrapper">

            <div class="inner">

                <section id="intro" class="section">

                    <div class="inner">

                        <h1 class="name" data-lang="product_title" data-altlang="product_title">YEEZY POWERPHASE</h1>
                        <p class="made-by" data-lang="product_made_by_2">design<br/>by<br/>Kanye West</p>

                        <!--<p class="select-color select-color-1" data-lang="product_color_select_1">Adult</p>-->
                        <!--<p class="select-color select-color-2" data-lang="product_color_select_2">Infant</p>-->
                        <!--<ul class="color-picker">-->
                            <!--<li data-color="red2" data-id="1" class="color color-1 active" data-lang="product_color_select_1">Adult</li>-->
                            <!--<li data-color="red2-infant" data-id="2" class="color color-2" data-lang="product_color_select_2">Infant</li>-->
                        <!--</ul>-->

                        <p class="mx-legal hidden">El acceso habilitado a esta página no garantiza ninguna promesa de compra u oferta para el calzado Yeezy Boost 350 (en adelante el producto) por parte de adidas de México, S.A de C.V. El comprador deberá mantener abierto este sitio para permanecer en la fila de acceso a compra y no perder su turno. Venta de producto limitado hasta agotar existencia. En caso de acceder a la compra del producto la compra será limitada a un par por comprador. No se garantiza disponibilidad de tallas. Venta dirigida a mayores de edad. Aplican términos y condiciones de compra establecidos en <a href="http://adidas.mx">www.adidas.mx</a>.</p>
                    </div>

                </section>

                <section id="gallery" class="section">

                    <div class="inner">

                        <div class="shoe-gallery shoe-gallery-adult">

                            <div class="item"><img data-src="/vp_assets/images/powerphase/adidas_YEEZY_POWERPHASE_left.jpg" alt="Yeezy" class="lazyOwl"></div>
                            <div class="item"><img data-src="/vp_assets/images/powerphase/adidas_YEEZY_POWERPHASE_right.jpg" alt="Yeezy" class="lazyOwl"></div>
                            <div class="item"><img data-src="/vp_assets/images/powerphase/adidas_YEEZY_POWERPHASE_front.jpg" alt="Yeezy" class="lazyOwl"></div>
                            <div class="item"><img data-src="/vp_assets/images/powerphase/adidas_YEEZY_POWERPHASE_top.jpg" alt="Yeezy" class="lazyOwl"></div>
                            <div class="item"><img data-src="/vp_assets/images/powerphase/adidas_YEEZY_POWERPHASE_bottom.jpg" alt="Yeezy" class="lazyOwl"></div>

                        </div>

                    </div>

                </section>

                <div class="clearfix"></div>

            </div>

        </section>

        <!--<section id="description" class="section">-->

            <!--<div class="inner">-->
                <!--<p data-lang="product_description" data-altlang="product_description"></p>-->
            <!--</div>-->

        <!--</section>-->

        <div class="hidden">
            <div id="getupdatesModal">
                <div id="getupdates">
                    <iframe style="height: 720px;" src="" class="updates-iframe"></iframe>
                </div>
            </div>
            <div id="badBrowserModal">
                <div id="badBrowser">
                    <h3 data-lang="unsupported_browser">Sorry! Your browser isn't supported.<br> Please update to a modern browser.</h3>
                </div>
            </div>
        </div>

        <!-- FOOTER START -->
        <div class="bottom-spacer"></div>

        <footer class="bottom">
            <div class="inner">
                <ul class="links">
                    <li class="link hidden">
                        <a href="#" data-url="sitemap" data-lang="footer_sitemap_name">
                            Sitemap
                        </a>
                    </li>
                    <li class="link hidden">
                        <a href="#" data-url="cookies" data-lang="footer_cookies_name">
                            Cookies
                        </a>
                    </li>
                    <li class="link">
                        <a href="#" data-url="privacy" data-lang="footer_privacy_name">
                            Privacy Policy
                        </a>
                    </li>
                    <li class="link">
                        <a href="#" data-url="terms" data-lang="footer_terms_name">
                            Terms and Conditions
                        </a>
                    </li>
                    <li class="link">
                        <a href="#" data-url="imprint" data-lang="footer_imprint_name">
                            Imprint
                        </a>
                    </li>
                </ul>
            </div>
        </footer>
        <!-- FOOTER END -->

    </div>
    <!-- CONTENT END -->

    <script>
        // Load translation, but only for non US since that is default language loaded already.
        function translation()
        {
            if (LANGUAGE !== 'en_US')
            {
                // Set path to translation file
                var translationFile = LANGUAGE_LOCATION+LANGUAGE+'.json?v=19';

                // Get translation
                $.getJSON(translationFile, function(result){
                    $.each(result, function(i, string){
                        // Update copy
                        $('[data-lang="'+i+'"]').html(string);

                        // Update urls
                        $('[data-lang-url="'+i+'"]').attr('href', string);
                    });
                });
            }
        }

        // set market urls
        function marketUrls()
        {
            var urlPart = {
                "AR": {
                    "men": "hombres",
                    "women": "mujeres",
                    "kids": "ninos",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "AT": {
                    "men": "manner",
                    "women": "frauen",
                    "kids": "kinder",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "AU": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "BE": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "BR": {
                    "men": "homem",
                    "women": "mulher",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "CA": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "CH": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "CL": {
                    "men": "hombre",
                    "women": "mujer",
                    "kids": "ninos",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "CN": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "CO": {
                    "men": "hombre",
                    "women": "mujer",
                    "kids": "ninos",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "CZ": {
                    "men": "muzi",
                    "women": "zeny",
                    "kids": "deti",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "DE": {
                    "men": "manner",
                    "women": "frauen",
                    "kids": "kinder",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "DK": {
                    "men": "maend",
                    "women": "kvinder",
                    "kids": "born",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "EE": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "ES": {
                    "men": "hombre",
                    "women": "mujer",
                    "kids": "ninos",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "FI": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "FR": {
                    "men": "hommes",
                    "women": "femmes",
                    "kids": "enfants",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "GB": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "GR": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "HK": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "HU": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "ID": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "IE": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "IN": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "IT": {
                    "men": "uomo",
                    "women": "donna",
                    "kids": "bambino",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "JP": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "KR": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "KW": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "MX": {
                    "men": "hombre",
                    "women": "mujer",
                    "kids": "ninos",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "MY": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "NG": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "NL": {
                    "men": "heren",
                    "women": "dames",
                    "kids": "kinderen",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "NO": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "NZ": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "PE": {
                    "men": "hombre",
                    "women": "mujer",
                    "kids": "ninos",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "PH": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "PL": {
                    "men": "mezczyzni",
                    "women": "kobiety",
                    "kids": "dzieci",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "PT": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "RU": {
                    "men": "muzhchiny",
                    "women": "zhenshchiny",
                    "kids": "deti",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "SE": {
                    "men": "herr",
                    "women": "dam",
                    "kids": "barn",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "SG": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "SK": {
                    "men": "muzi",
                    "women": "zeny",
                    "kids": "deti",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "TH": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "TR": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "TW": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "US": {
                    "men": "us/men",
                    "women": "us/women",
                    "kids": "us/kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "us/help-topics-sitemap.html",
                    "cookies": "us/help-topics-privacy_policy.html#cookies",
                    "privacy": "us/help-topics-privacy_policy.html",
                    "terms": "us/help-topics-terms_and_conditions.html",
                    "imprint": "us/help-topics-imprint.html"
                },
                "VE": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "VN": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "ZA": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                },
                "COM": {
                    "men": "men",
                    "women": "women",
                    "kids": "kids",
                    "my_account": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/MyAccount-CreateOrLogin",
                    "cart": "on/demandware.store/Sites-adidas-{{MARKET}}-Site/{{LOCALE}}/Cart-Show",
                    "sitemap": "help-topics-sitemap.html",
                    "cookies": "help-topics-privacy_policy.html#cookies",
                    "privacy": "help-topics-privacy_policy.html",
                    "terms": "help-topics-terms_and_conditions.html",
                    "imprint": "help-topics-imprint.html"
                }
            };

            var market = MARKET;
            if (market === 'UK') {
                market = 'GB';
            }

            if (market === 'CF') {
                market = 'CA';
            }

            var prefix = 'www.';
            if (DEVICE === 'mobile') {
                prefix = 'm.';
            }

            var append = '';
            if (market === 'US') {
                append = 'us';
            } else if (market === 'CA') {
                append = 'en';
            } else if (market === 'CF') {
                append = 'fr';
            } else if (market === 'PT') {
                append = 'pt';
            }

            $('[data-url]').each(function(i, el){
                var urlName = $(el).attr('data-url');

                if (urlName === 'my_account' || urlName === 'cart')
                {
                    var url = urlPart[MARKET][urlName].replace('{{MARKET}}', MARKET).replace('{{LOCALE}}', LANGUAGE);
                    $(el).attr('href', window.location.protocol + '//' + prefix + MARKETS[MARKET]['domain'] + '/' + url);
                }
                else if (urlName === 'home')
                {
                    $(el).attr('href', window.location.protocol + '//' + prefix + MARKETS[MARKET]['domain'] + '/' + append);
                }
                else
                {
                    $(el).attr('href', window.location.protocol + '//' + prefix + MARKETS[MARKET]['domain'] + '/' + urlPart[MARKET][urlName]);
                }

            });
        }

        // For the CSS spinner
        function browserSupportsCSSProperty(propertyName)
        {
            var elm = document.createElement('div');
            propertyName = propertyName.toLowerCase();

            if (elm.style[propertyName] != undefined)
                return true;

            var propertyNameCapital = propertyName.charAt(0).toUpperCase() + propertyName.substr(1),
            domPrefixes = 'Webkit Moz ms O'.split(' ');

            for (var i = 0; i < domPrefixes.length; i++) {
                if (elm.style[domPrefixes[i] + propertyNameCapital] != undefined)
                return true;
            }

            return false;
        }

        // Randomly display a any of the 3 messages
        function displayRandomMessage()
        {
            var messageNum = Math.floor(Math.random() * 3) + 1;
            $('body .message-'+messageNum).removeClass('hidden');
        }

        // Display fallback image loader for browser not supporting animations, like old IE
        if (!browserSupportsCSSProperty('animation')) {
          $('.spinner .sk-fading-circle').hide();
          $('.spinner img').show();
        }

        displayRandomMessage();
        translation();
        marketUrls();

        // Display legal for Mexico (MX) market only
        if (MARKET === 'MX') {
            $('body #intro .inner').addClass('mx-disclaimer');
            $('body .mx-legal').removeClass('hidden');
        }

        //
        // Change copy of different products
        //
        $('body .item-picker').on('click', '.color', function(e) {

            var id = $(this).data('id');

            $.getJSON(LANGUAGE_LOCATION+LANGUAGE+'.json', function(json) {
                $('*[data-altlang]').each(function () {
                    var $el, copyKey;
                    $el = $(this);
                    copyKey = $el.data('altlang');
                    if (id === 2) {
                        return $el.html(json[copyKey + '_p2']);
                    } else {
                        return $el.html(json[copyKey]);
                    }
                });
            });
        });

    </script>

</body>
</html>

