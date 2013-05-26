
# Maven Tycho

you can use tycho to update version numbers for the pom.xml and manifest at the same time:

	mvn -Dtycho.mode=maven org.eclipse.tycho:tycho-versions-plugin:set-version -DnewVersion=Major.Minor.Patch-SNAPSHOT


#Tools

[Musoftware Icons Extractor](http://sourceforge.net/projects/muie) for getting icons from exe, dll and previewing (with all sizes)