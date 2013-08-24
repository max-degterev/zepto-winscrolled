zepto-winscrolled
=================

Solution for realtime scroll event on mobile

Usage:

Instead of

  $(window).on('scroll', function(e){});

use:

  $(window).on('winscrolled', function(e){ console.warn(e.data) });
