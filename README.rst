==================================
Django-Rest-Snippets support for Sublime Text 3
==================================

Overview
--------

Installation
------------

1. Clone this repo
2. Put the contents of this repo directly inside:

 - OS X: ~/Library/Application\\ Support/Sublime\\ Text\\ 3/Packages
 - Windows: %APPDATA%/Sublime Text 3/Packages/
 - Linux: ~/.config/sublime-text-3/Packages

Or use PackageControl.

Snippets for Django REST serializer fields
---------------------------------
=============== ======================================================
 Abbreviation                        Tag
=============== ======================================================
 sbool          ``serializers.BooleanField()``
 schar        ``serializers.CharField()``
 schoice          ``serializers.ChoiceField()``
 sdate          ``serializers.DateField()``
 sdatetime       ``serializers.DateTimeField()``
 sdecimal          ``serializers.DecimalField()``
 sdict      ``serializers.DictField()``
 sduration       ``serializers.DurationField()``
 semail      ``serializers.EmailField()``
 sfile         ``serializers.FileField()``
 sfilepath          ``serializers.FilePathField()``
 sfloat      ``serializers.FloatField()``
 shidden         ``serializers.HiddenField()``
 shiperidentity           ``serializers.HyperlinkedRelatedField()``
 shr           ``serializers.HyperlinkedRelatedField()``
 simage            ``serializers.ImageField()``
 sint      ``serializers.IntegerField()``
 sip         ``serializers.IPAddressField()``
 sjson        ``serializers.JSONField()``
 slist   ``serializers.ListField()``
 smodel          ``serializers.ModelField()``
 smchoice      ``serializers.MultipleChoiceField()``
 snullbool          ``serializers.NullBooleanField()``
 spkr          ``serializers.PrimaryKeyRelatedField()``
 sreadonly           ``serializers.ReadOnlyField()``
 sregex       ``serializers.RegexField()``
 ssmethod           ``serializers.SerializerMethodField()``
 sslug             ``serializers.SlugField()``
 sslugrelated            ``serializers.SlugRelatedField()``
 ssr            ``serializers.StringRelatedField()``
 stime            ``serializers.TimeField()``
 surl            ``serializers.URLField()``
 suuid            ``serializers.UUIDField()``
=============== ======================================================

Snippets for Django REST serializer methods
--------------------------------
=============== ======================================================
 Abbreviation                        Tag
=============== ======================================================
 create          ``def create(self, validated_data)``
 update        ``def update(self, instance, validated_data)``
===============================

Snippets for Django REST serializer classes
--------------------------------
=============== ======================================================
 Abbreviation                        Tag
=============== ======================================================
 serializer          ``Serializer``
 modelserializer        ``Model Serializer``
===============================

Completions
------------

    Full list of all available settings

- read_only
- write_only
- required
- allow_null