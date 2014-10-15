maps-component-archetype
========================

Scaffolds the 4 bundles of Maps Components  : persistence , persistence service, rest, webcontent

1. Create artifact and upload to local repo : mvn clean install
2. Create Component from archetype: 
      mvn archetype:generate 
      -DarchetypeGroupId=com.avon.archetype 
      -DarchetypeVersion=1.0 
      -DarchetypeArtifactId=com.avon.archetype.component 
      -DgroupId=com.avon 
      -Dversion=0.0.1-SNAPSHOT

2b.Interactiv console (sample):

  package=com.avon
  groupId=com.avon
  artifactId=com.avon.maps.offer
  version=0.1-SNAPSHOT
  
  Generate directory path:
  dir=maps/offer/  ---- (artifactid minus groupId with '/')
  
  module-description=Module description
  angular-name=offer
  webcontent-priority=1
  
3. Copy the generated directories to MAPS (Don't copy the generated com.avon.prototype directory and the outer pom.xlm .They are just for technically purpose.)

=================================

