===============================================
Django-Rest-Snippets support for Sublime Text 3
===============================================

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

Snippets for serializer fields
------------------------------------------
=============== ======================================================
 Abbreviation                        Tag
=============== ======================================================
 sbool          ``serializers.BooleanField()``
 schar          ``serializers.CharField()``
 schoice        ``serializers.ChoiceField()``
 sdate          ``serializers.DateField()``
 sdatetime      ``serializers.DateTimeField()``
 sdecimal       ``serializers.DecimalField()``
 sdict          ``serializers.DictField()``
 sduration      ``serializers.DurationField()``
 semail         ``serializers.EmailField()``
 sfile          ``serializers.FileField()``
 sfilepath      ``serializers.FilePathField()``
 sfloat         ``serializers.FloatField()``
 shidden        ``serializers.HiddenField()``
 shiperidentity ``serializers.HyperlinkedRelatedField()``
 shr            ``serializers.HyperlinkedRelatedField()``
 simage         ``serializers.ImageField()``
 sint           ``serializers.IntegerField()``
 sip            ``serializers.IPAddressField()``
 sjson          ``serializers.JSONField()``
 slist          ``serializers.ListField()``
 smodel         ``serializers.ModelField()``
 smchoice       ``serializers.MultipleChoiceField()``
 snullbool      ``serializers.NullBooleanField()``
 spkr           ``serializers.PrimaryKeyRelatedField()``
 sreadonly      ``serializers.ReadOnlyField()``
 sregex         ``serializers.RegexField()``
 ssmethod       ``serializers.SerializerMethodField()``
 sslug          ``serializers.SlugField()``
 sslugrelated   ``serializers.SlugRelatedField()``
 ssr            ``serializers.StringRelatedField()``
 stime          ``serializers.TimeField()``
 surl           ``serializers.URLField()``
 suuid          ``serializers.UUIDField()``
=============== ======================================================

Snippets for serializer methods
-------------------------------------------
=============== ======================================================
 Abbreviation                        Tag
=============== ======================================================
 create         ``def create(self, validated_data)``
 update         ``def update(self, instance, validated_data)``
=============== ======================================================

Snippets for serializer classes
-------------------------------------------
================ ======================================================
 Abbreviation                        Tag
================ ======================================================
 serializer      ``Serializer``
 modelserializer ``Model Serializer``
================ ======================================================

Snippets for Concrete View Classes
----------------------------------
============================= =========================================
 Abbreviation                        Tag
============================= =========================================
 apiview                      ``APIView``
 createapiview                ``CreateAPIView``
 destroyapiview               ``DestroyAPIView``
 listapiview                  ``ListAPIView``
 listcreateapiview            ``ListCreateAPIView``
 retrieveapiview              ``RetrieveAPIView``
 retrievedestroyapiview       ``RetrieveDestroyAPIView``
 retrieveupdateapiview        ``RetrieveUpdateAPIView``
 retrieveupdatedestroyapiview ``RetrieveUpdateDestroyAPIView``
 updateapiview                ``UpdateAPIView``
============================= =========================================

Snippets for View Methods
-------------------------
============================= =========================================
 Abbreviation                        Tag
============================= =========================================
 perfomecreate                ``perform_create``
 perfomedelete                ``perform_destroy``
 perfomeupdate                ``perform_update``
============================= =========================================

Snippets for ViewSet
--------------------
===================== =================================================
 Abbreviation                        Tag
===================== =================================================
 viewset              ``ViewSet``
 readonlymodelviewset ``ReadOnlyModelViewSet``
 modelviewset         ``ModelViewSet``
===================== =================================================

Completions
-----------

    Full list of all available settings

- read_only
- write_only
- required
- allow_null