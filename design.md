##Overall

The objective is to have a software platform that can be easily customized to fit any election anywhere in the world.<br>
    The current language is English, but can be translated into other languages once it has been proven.<br>
    Hopefully, we will have an open source product that will handle most elections with no modification, other than to the database.<br>
        But the source code should be available to be copied and modified as need.<br>  
            Elections in Nigeria, for example, may have significant differences that cannot be anticipated in a database.<br>

There will be 3 major components to the platform:
    A database that contains the information needed to customize the platform for a particular election.<br>
    A Web Site that is available to the public with the topic and responses from the candidates.<br>
    A web site that will administer the forum and customize the database.<br>
Details of each of these components will be found in other entries

The web site to present the Forum is driven based on values in the database.<br>

The web site to present the Forum will have a basic structure, which will be populated by the customized database.<br>
    An appropriate CMS (or similar) tool will need to be chosen.<br>  
        It appears that WordPress may not be the ideal choice.<br>

The web site to administer the Forum for a particular election.<br>
    The specs for the database customization should be fairly obvious once the database design is complete.<br>
    The specs for the administration of the Forum are not clear at this point.<br>
        It may involve issues like:
            hosting site
            credentials for administrator roles

? What needs to be taken into consideration to facilitate translations into other languages.<br>

It may make sense to develop this in phases
	1.<br> Build a model that can handle a particular election, in English, with a manually administered database
	2.<br> Build the administration web site based on the phase 1 experience
	3.<br> Build the fully portable model based on the phase 2 experience.<br>

Of course, each phase would incorporate best practices to make later phases easier.<br>

? Are there other names for the project that might be better, e.<br>g.<br> TransparentElections.<br>
    the .<br>us for the current domains might not be best for the final product.<br>

Security will be a major issue at all levels.<br>