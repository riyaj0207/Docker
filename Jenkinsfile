node {

    

    docker.withRegistry('sekadocker.epk.ericsson.se/proj-em-dev/test/eric-em-customreport:2.9.0-${BUILD_NUMBER}', 'AP5tA9CJTmKAm7eB1Q6kGroMhXK') {

        def customImage = docker.build("/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
