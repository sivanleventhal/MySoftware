node {
    stage("clone"){
        git "https://github.com/sivanleventhal/MySoftware.git"
    }
    stage("click"){
        bat "python click.py"
    }
    stage("welcome"){
        bat "python welcome.py"
    }
}
