 find . -type d -maxdepth 1 -mindepth 1 -exec bash -c "cd {} && npm pack && mv *.tgz ../" \;
