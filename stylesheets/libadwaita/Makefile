.PHONY: all clean

all: default.css high-contrast.css

%.css: %.scss _colors.scss _common.scss _compat-colors.scss _drawing.scss _palette.scss _widgets.scss widgets/_avatar.scss widgets/_bottom-sheet.scss widgets/_buttons.scss widgets/_calendar.scss widgets/_checks.scss widgets/_color-chooser.scss widgets/_column-view.scss widgets/_deprecated.scss widgets/_dialogs.scss widgets/_dropdowns.scss widgets/_emoji-chooser.scss widgets/_entries.scss widgets/_expanders.scss widgets/_file-chooser.scss widgets/_header-bar.scss widgets/_inspector.scss widgets/_labels.scss widgets/_level-bar.scss widgets/_linked.scss widgets/_links.scss widgets/_lists.scss widgets/_menus.scss widgets/_message-dialog.scss widgets/_misc.scss widgets/_notebook.scss widgets/_paned.scss widgets/_popovers.scss widgets/_preferences.scss widgets/_progress-bar.scss widgets/_scale.scss widgets/_scrolling.scss widgets/_shortcuts-dialog.scss widgets/_sidebars.scss widgets/_spinner.scss widgets/_spin-button.scss widgets/_switch.scss widgets/_tab-view.scss widgets/_text-selection.scss widgets/_toggle-group.scss widgets/_toolbars.scss widgets/_tooltip.scss widgets/_views.scss widgets/_view-switcher.scss widgets/_window.scss
	sassc -a -M -t compact $< $@

clean:
	rm -f default.css high-contrast.css
