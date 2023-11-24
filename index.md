<html>
	<body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00D5i00000DzdKC',
				'New_Web_Site',
				'https://fortrea2-dev-ed.develop.my.site.com/ESWNewWebSite1700841241770',
				{
					scrt2URL: 'https://fortrea2-dev-ed.develop.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://fortrea2-dev-ed.develop.my.site.com/ESWNewWebSite1700841241770/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  
</body>
</html>
