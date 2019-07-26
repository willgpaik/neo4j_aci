BootStrap: shub
From: willgpaik/centos7_aci

%setup

%files

%environment

%runscript

%post
    rpm --import https://debian.neo4j.org/neotechnology.gpg.key
    cat <<EOF>  /etc/yum.repos.d/neo4j.repo
    [neo4j]
    name=Neo4j RPM Repository
    baseurl=https://yum.neo4j.org/stable
    enabled=1
    gpgcheck=1
    EOF
    yum -y install neo4j-3.5.8
    
    yum -y update
