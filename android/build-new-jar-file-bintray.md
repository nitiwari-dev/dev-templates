Steps:

1. Change the version within the library project module's build.gradle ext {} section 
2. Added below lines within modules build.gradle

//These two remote files contain Bintray configuration as described above.
apply from: 'https://raw.githubusercontent.com/nitiwari-dev/dev-templates/master/android/bintray.gradle'
apply from: 'https://raw.githubusercontent.com/nitiwari-dev/dev-templates/master/android/install.gradle'

3. Commit and run the project
