# !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
# NOTE: DO *NOT* EDIT THIS FILE.  IT IS GENERATED.
# PLEASE UPDATE Dockerfile.txt INSTEAD OF THIS FILE
# !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
FROM selenium/base:4.0.0-alpha-7-prerelease-20201009
LABEL authors=SeleniumHQ

USER 1200

#========================
# Selenium Router Configuration
#========================

EXPOSE 4444

COPY start-selenium-grid-router.sh \
    /opt/bin/

COPY selenium-grid-router.conf /etc/supervisor/conf.d/
