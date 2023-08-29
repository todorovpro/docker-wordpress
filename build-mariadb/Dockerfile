ARG MARIADB_VERSION

FROM mariadb:${MARIADB_VERSION}

# COPY php-custom.ini $PHP_INI_DIR/conf.d/

ADD http://mysqltuner.pl/ /opt/mysqltuner/mysqltuner.pl
ADD https://raw.githubusercontent.com/major/MySQLTuner-perl/master/basic_passwords.txt /opt/mysqltuner/basic_passwords.txt
ADD https://raw.githubusercontent.com/major/MySQLTuner-perl/master/vulnerabilities.csv /opt/mysqltuner/vulnerabilities.csv
