requirejs.config({
	// baseUrl의 경우 runtime에 결정되므로 아래에서 재정의
	paths : {
		'jquery' : '_libs/jquery/jquery-1.11.3.min',
		'underscore' : '_libs/underscore/underscore-1.8.3',
        'underscore.string' : '_libs/underscore/underscore.string-2.4.0',
		'backbone' : '_libs/backbone/backbone-1.3.3',
		'backbone.courier' : '_libs/backbone/marionette/backbone.courier-2.0.0',
		'backbone.babysitter' : '_libs/backbone/babysitter/backbone.babysitter',
        'marionette' : '_libs/backbone/marionette/backbone.marionette-3.2.0',
        'backbone.marionette' : '_libs/backbone/marionette/backbone.marionette-3.2.0',
        'backbone.radio' : '_libs/backbone/marionette/backbone.radio-2.0.0',
		'moment' : '_libs/moment/moment-2.9.0',
		'moment-timezone' : '_libs/moment/moment-timezone-with-data-0.5.13',
        // TODO: moment.range 인데, IntelliJ가 moment.range 라고 쓰면 warning 표시를 한다 일단 DateRange 라고 쓰고 정리방법은 나중에 고민하자.
		'date-range' : '_libs/moment/moment-range-2.0.2',
		'clndr' : '_libs/clndr/clndr-1.2.3',
		'text' : '_libs/requirejs/plugin/text-2.0.12',
		'sjcl' : '_libs/sjcl/sjcl',
		'json2' : '_libs/json2/json2',
		'socketIO' : '_libs/chat/socket.io-1.3.5',
		'chatClient' : '_libs/chat/simple-chat-client',
		'ckeditor' : '_libs/ckeditor/ckeditor',
        'jscache' : '_libs/jscache/jscache',
		'odometer' : '_libs/odometer/odometer-0.4.6',
		'jquery.dotdotdot': '_libs/jquery/plugin/jquery.dotdotdot_custom'
	},
	shim : {
        'app_base' : {
            deps : ['base_libs']
        },
		'underscore.string' : {
			deps : ['underscore']
		},
		'backbone.courier' : {
			deps : ['backbone', 'underscore']
		},
        'backbone.babysitter' : {
            deps : ['backbone']
        },
		'clndr' : {
			deps : [ 'jquery', 'underscore', 'moment']
		},
		'sjcl' : {
			exports : 'sjcl'
		},
		'json2' : {
			exports : 'JSON'
		},
        'ckeditor' : {
			exports : 'CKEDITOR'
		},
        '_libs/jquery/plugin/jquery.cookie' : {
            deps : [ 'jquery']
        },
		'_libs/jquery/plugin/jquery.nanoScroll' : {
            deps : [ 'jquery']
        },
		'_libs/jquery/plugin/jquery.browser' : {
			deps : [ 'jquery']
		},
        '_libs/jquery/plugin/jquery-ui' : {
            deps : [ 'jquery' ]
        },
		'_libs/jquery/plugin/jquery.ua' : {
			deps : [ 'jquery' ]
		},
        '_libs/jquery/plugin/jquery.scrollTo' : {
            deps : [ 'jquery' ]
        },
		'_libs/jquery/plugin/jquery.Jcrop' : {
			deps : [ 'jquery' ]
		},
		'_libs/jquery/plugin/chosen.jquery' : {
			deps : [ 'jquery' ]
		},
		'_band_libs/image/jquery.image.setLoading' : {
			deps : [ 'jquery' ]
		},
        '_libs/jquery/plugin/jquery.touchSwipe' : {
            deps : [ 'jquery' ]
        },
        'jquery.dotdotdot' : {
            deps : [ 'jquery' ]
        },
        '_libs/jquery/plugin/jquery.sticky.custom' : {
            deps : [ 'jquery' ]
        },
        '_libs/Intl/Intl' : {
            exports : "Intl"
        },
        '_libs/formatjs/intl-messageformat/intl-messageformat' : {
            exports : "IntlMessageFormat"
        },
        '_libs/formatjs/intl-relativeformat/intl-relativeformat' : {
            exports : "IntlRelativeFormat"
        },
		'_libs/iscroll/iscroll' : {
			exports : "IScroll"
		},
		'_libs/fileApi/FileAPI_custom' : {
			deps : ['jquery','_libs/jquery/plugin/jquery.browser','_libs/_custom/FileAPIPrepare'],
			exports : "FileAPI"
		},
		'_libs/swipeview/swipeview_custom' : {
			exports : "CustomSwipeView"
		},
		'_libs/fileApi/jquery.fileapi_custom' : {
			deps : ['jquery','_libs/fileApi/FileAPI_custom', '_libs/jquery/plugin/jquery.Jcrop']
		},
		'_libs/jquery/plugin/jquery.jplayer' : {
			deps : [ 'jquery' ]
        },
        '_libs/_custom/mention/jquery.elastic.heightcustom' : {
            deps : [ 'jquery' ]
        },
        '_libs/_custom/mention/jquery.mentionsInput.customByBand' : {
            deps : [ 'jquery', 'underscore', '_libs/_custom/mention/jquery.elastic.heightcustom']
        },
        '_libs/jquery/plugin/jquery.autoNumeric' : {
            deps : [ 'jquery' ]
        },
		'_libs/mediaelement/mediaelement-and-player_dCustom' : {
			deps : [ 'jquery' ],
            exports: 'mejs'
		},
		'_libs/mediaelement/mediaelement-and-player_mCustom' : {
			deps : [ 'jquery' ]
		},
        '_libs/flxhr/swfobject' : {
            exports : 'swfobject'
        },
        '_libs/flxhr/checkplayer' : {
            deps : [ '_libs/flxhr/swfobject']
        },
        '_libs/flxhr/flensed' : {
            deps : [ '_libs/flxhr/swfobject', '_libs/flxhr/checkplayer']
        },
        '_libs/flxhr/flXHR' : {
            deps : [ '_libs/flxhr/swfobject','_libs/flxhr/checkplayer', '_libs/flxhr/flensed']
        },
        '_libs/jquery/plugin/jquery.flXHR' : {
            deps : [ 'jquery', '_libs/flxhr/flXHR']
        },
        '_libs/jquery/plugin/jquery.titlealert' : {
            deps : [ 'jquery']
        },
        '_band_libs/element/jquery.scrollUtil' : {
            deps : [ 'jquery' ]
        },
		'_libs/imageViewer/imageviewer_custom' : {
			deps : [ 'jquery' ]
		},
        '_libs/moment/moment-timezone-with-data-0.5.13' : {
            deps : [ 'moment' ]
		},
		'_libs/moment/moment-range-2.0.2' : {
        	deps : [ 'moment' ]
		},
		'_libs/sortable/Sortable_custom' : {
			deps : ['jquery', '_libs/jquery/plugin/jquery.browser'],
			exports : 'Sortable'
		},
		'_band_libs/polyfill/intersection-observer' : {
			deps : [ 'jquery', '_libs/jquery/plugin/jquery.browser' ]
		},
		'odometer' : {
        	deps : ['jquery']
		}
    },
    wrapShim: true,
	waitSeconds: 240
});

requirejs.config({
	baseUrl : (window.scriptBaseUrl) ? window.scriptBaseUrl : "/script",
	"urlArgs" : (window.version)? "_=" + window.version : ""
});
