build_overview:
	@echo Building overview deck
	@md2gslides ./1-overview/overview.md -t "QCon 2019 - Service mesh overview" -n -c ${DEFAULT_TEMPLATE} -s nord

update_overview:
	@echo Updating overview deck
	@md2gslides ./1-overview/overview.md -a ${WHATIS_DECK_ID} -e -n -s nord

build_security:
	@echo Building security deck
	@md2gslides ./2-security/security.md -t "QCon 2019 - Security" -n -c ${DEFAULT_TEMPLATE} -s nord

update_security:
	@echo Updating security deck
	@md2gslides ./2-security/security.md -a ${SECURITY_DECK_ID} -e -n -s nord

build_observability:
	@echo Building observability deck
	@md2gslides ./3-observability/observability.md -t "QCon 2019 - Observability" -n -c ${DEFAULT_TEMPLATE} -s nord

update_observability:
	@echo Updating observability deck
	@md2gslides ./3-observability/observability.md -a ${OBSERVABILITY_DECK_ID} -e -n -s nord

build_reliability:
	@echo Building reliability deck
	@md2gslides ./4-reliability/reliability.md -t "QCon 2019 - Reliability" -n -c ${DEFAULT_TEMPLATE} -s nord

update_reliability:
	@echo Updating reliability deck
	@md2gslides ./4-reliability/reliability.md -a ${RELIABILITY_DECK_ID} -e -n -s nord
