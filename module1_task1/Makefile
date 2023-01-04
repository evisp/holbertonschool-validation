clean:
	rm -rf ./dist/

build:
	hugo

post:
	hugo new posts/$(POST_NAME).md
	sed -i '/title:/c\title: "$(POST_TITLE)"' content/posts/$(POST_NAME).md
