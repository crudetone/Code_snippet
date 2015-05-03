FullHeight
function addFullheight(fullh){
		fullh.each(function(){
			if($(this).hasClass('fullheight')){
				$(this).height($(window).height());
			}
		});
	}
------------------------------------------------------------------
FullBackground
function addFullbg(fullbg){
		fullbg.each(function(){
			if($(this).attr('data-background')){
				$(this).css('background-image','url(' + $(this).attr('data-background') + ')');
			}
		})
	}
------------------------------------------------------------------
