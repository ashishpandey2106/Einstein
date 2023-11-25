<html>
	<body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DHu000002gqZn',
				'New_Web_Channel',
				'https://in1700932705855.my.site.com/ESWNewWebChannel1700936932050',
				{
					scrt2URL: 'https://in1700932705855.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://in1700932705855.my.site.com/ESWNewWebChannel1700936932050/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

</body>
</html>
