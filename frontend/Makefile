BUILD_DIR              = build
GULP                   = node_modules/.bin/gulp

devel:
	yarn install
	$(GULP) devel

prod:
	yarn install --network-timeout 1000000
	$(GULP) prod

clean:
	-rm -rf $(BUILD_DIR);
