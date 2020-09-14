node {

    

    docker.withRegistry('https://arm.seli.gic.ericsson.se/artifactory//proj-em-dev/test/', 'AP5tA9CJTmKAm7eB1Q6kGroMhXK') {

        def customImage = docker.build("dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
