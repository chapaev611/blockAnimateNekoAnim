<!-- Animate Scripts -->

function resizeAnimate() {

	if($(window).width() >= '992') {

		// FADE IN UP
		$('.animFadeInUp').addClass('nekoAnim-invisible').viewportChecker({
			classToAdd: 'nekoAnim-visible nekoAnim-animated nekoAnim-fadeInUp',
			offset: 250
		})
		//FADE IN RIGHT
		$('.animFadeInRight').addClass('nekoAnim-invisible').viewportChecker({
			classToAdd: 'nekoAnim-visible nekoAnim-animated nekoAnim-fadeInRight',
			offset: 250
		})
		//FADE IN LEFT
		$('.animFadeInLeft').addClass('nekoAnim-invisible').viewportChecker({
			classToAdd: 'nekoAnim-visible nekoAnim-animated nekoAnim-fadeInLeft',
			offset: 250
		})

	}
} 


$(window).on('load resize', resizeAnimate);
