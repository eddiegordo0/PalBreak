GO_EASY_ON_ME = 1

include $(THEOS)/makefiles/common.mk

BUNDLE_NAME = NoSub
NoSub_FILES = nosubRootListController.m
NoSub_INSTALL_PATH = /Library/PreferenceBundles
NoSub_FRAMEWORKS = UIKit
NoSub_PRIVATE_FRAMEWORKS = Preferences

include $(THEOS_MAKE_PATH)/bundle.mk

internal-stage::
	$(ECHO_NOTHING)mkdir -p $(THEOS_STAGING_DIR)/Library/PreferenceLoader/Preferences$(ECHO_END)
	$(ECHO_NOTHING)cp entry.plist $(THEOS_STAGING_DIR)/Library/PreferenceLoader/Preferences/NoSub.plist$(ECHO_END)
