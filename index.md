<html>
    <body>
        <script type='text/javascript'>
            function initEmbeddedMessaging() {
                try {
                    embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
        
                    embeddedservice_bootstrap.init(
                        '00DHu00000R9Yl5',
                        'SDO_Messaging_for_Web',
                        'https://storm-132899f2c6eeed.my.site.com/ESWSDOMessagingforWeb1747393799879',
                        {
                            scrt2URL: 'https://storm-132899f2c6eeed.my.salesforce-scrt.com'
                        }
                    );
                } catch (err) {
                    console.error('Error loading Embedded Messaging: ', err);
                }
            };
        </script>
        <script type='text/javascript' src='https://storm-132899f2c6eeed.my.site.com/ESWSDOMessagingforWeb1747393799879/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
    </body>
</html>
