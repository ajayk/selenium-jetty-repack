Relocates & Deploys Jetty with sources and javadocs to maven central
===================================================================

To deploy:

Check the versions in the pom, you need to update the jetty version
AND the actual project version to match.

mvn -Prelease deploy

go to oss.sonatype.org, close the staging repo, test and release.

