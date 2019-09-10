FROM composer:latest

LABEL "com.github.actions.name"="Composer"
LABEL "com.github.actions.description"="A GitHub action to run composer."
LABEL "com.github.actions.icon"="check-circle"
LABEL "com.github.actions.color"="orange"

LABEL "repository"="https://github.com/nandogameiro/actions"
LABEL "homepage"="https://github.com/nandogameiro/actions"
LABEL "maintainer"="Fernando Guedes <eu@fgued.es>"

COPY entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]