var reactive = {
    flipUpPx: function(name, speed, next) {
        var speedp = speed + 150;
        $(name).animate({
           top: '-=15'
        }, {duration: speed, queue: false});
        $(name).fadeOut('fast');
        window.setTimeout(replaceUp,speedp);
        function replaceUp () {
        $(name).html(next);
        $(name).fadeIn('fast');
        $(name).animate({
           top: '+=15'
        }, {duration: speed, queue: false});
        }
    },
    flipDownPx: function(name, speed, next) {
        var speedp = speed + 150;
        $(name).animate({
           top: '+=15'
        }, {duration: speed, queue: false});
        $(name).fadeOut('fast');
        window.setTimeout(replaceDown, speedp);
        function replaceDown () {
        $(name).html(next);
        $(name).fadeIn('fast');
        $(name).animate({
           top: '-=15'
        }, {duration: speed, queue: false});
        }
    },
    flipLeftPx: function(name, speed, next) {
        var speedp = speed + 150;
        $(name).animate({
           left: '-=15'
        }, {duration: speed, queue: false});
        $(name).fadeOut('fast');
        window.setTimeout(replaceLeft, speedp);
        function replaceLeft () {
        $(name).html(next);
        $(name).fadeIn('fast');
        $(name).animate({
           left: '+=15'
        }, {duration: speed, queue: false});
        }
    },
    flipRightPx: function(name, speed, next) {
        var speedp = speed + 150;
        $(name).animate({
           left: '+=15'
        }, {duration: speed, queue: false});
        $(name).fadeOut('fast');
        window.setTimeout(replaceRight, speedp);
        function replaceRight () {
        $(name).html(next);
        $(name).fadeIn('fast');
        $(name).animate({
           left: '-=15'
        }, {duration: speed, queue: false});
        }
    },
    flipVerticalUp: function(name, speed, next) {
        var speedp = speed + 150;
        $(name).animate({
           top: '-=15'
        }, {duration: speed, queue: false});
        $(name).fadeOut('fast');
        window.setTimeout(replaceDown,speedp);
        function replaceDown () {
        $(name).html(next);
        $(name).fadeIn('fast');
        $(name).css('margin-top', '+=30');
        $(name).animate({
           top: '-=15'
        }, {duration: speed, queue: false});
        }
    },
    flipVerticalDown: function(name, speed, next) {
        var speedp = speed + 150;
        $(name).animate({
           top: '+=15'
        }, {duration: speed, queue: false});
        $(name).fadeOut('fast');
        window.setTimeout(replaceDown,speedp);
        function replaceDown () {
        $(name).html(next);
        $(name).fadeIn('fast');
        $(name).css('margin-top', '-=30');
        $(name).animate({
           top: '+=15'
        }, {duration: speed, queue: false});
        }
    },
    flipHorizontalLeft: function(name, speed, next) {
        var speedp = speed + 150;
        $(name).animate({
           left: '-=15'
        }, {duration: speed, queue: false});
        $(name).fadeOut('fast');
        window.setTimeout(replaceRight, speedp);
        function replaceRight () {
        $(name).html(next);
        $(name).fadeIn('fast');
        $(name).css('margin-left', '+=30');
        $(name).animate({
           left: '-=15'
        }, {duration: speed, queue: false});
        }
    },
    flipHorizontalRight: function(name, speed, next) {
        var speedp = speed + 150;
        $(name).animate({
           left: '+=15'
        }, {duration: speed, queue: false});
        $(name).fadeOut('fast');
        window.setTimeout(replaceRight, speedp);
        function replaceRight () {
        $(name).html(next);
        $(name).fadeIn('fast');
        $(name).css('margin-left', '-=30');
        $(name).animate({
           left: '+=15'
        }, {duration: speed, queue: false});
        }
    }
};
