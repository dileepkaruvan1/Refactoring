# Refactoring

 * This is an utils class which will deploy the SCONSTRUCT and VERSION files to the
 * supplied source path as argument
 *
 * The deployed files files will have updated version number picked from the env property BuildNum.
 *
 * This class is used by the updateVersion.sh script to deploy to any env.
 *
 * The resources/build/templates directory have the template files with placeholder for the
 * version values which will be replaced while running the script.
