
APP = Black
NAMESPACE = com.maanoo.Black

run:
	./$(APP)

install:
	cp $(APP) ~/.local/bin/$(APP)
	mkdir -p ~/.local/share/applications
	cp $(NAMESPACE).desktop ~/.local/share/applications/$(NAMESPACE).desktop
	chmod +x ~/.local/share/applications/$(NAMESPACE).desktop
	mkdir -p ~/.local/share/icons/hicolor/scalable/apps
	cp $(NAMESPACE).svg ~/.local/share/icons/hicolor/scalable/apps/$(NAMESPACE).svg
