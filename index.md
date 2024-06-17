<html>
  <body>
    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; 
			embeddedservice_bootstrap.init(
				'00Dds00000005yz',
				'Help',
				'https://ott-summer--stage.sandbox.my.site.com/ESWHelp1717580897743',
				{
					scrt2URL: 'https://ott-summer--stage.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://ott-summer--stage.sandbox.my.site.com/ESWHelp1717580897743/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  </body>
</html>
