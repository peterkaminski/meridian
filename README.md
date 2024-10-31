# Meridian - A Time Zone Converter

To convert time zones, go directly to [meridian.html](/meridian.html).

Meridian is a streamlined, open source time zone converter that operates entirely within a single HTML and JavaScript file. It instantly generates copyable time listings across multiple time zones, perfect for coordinating across global teams or scheduling international events.

Unlike most converters, Meridian uses standard time zone abbreviations (such as EST, CEST, AEDT) rather than city names. This approach leverages local familiarity—while you might not know every time zone abbreviation worldwide, you'll certainly recognize your own. The converter automatically adjusts these abbreviations to reflect daylight savings time, summer time, or standard time based on the selected date and time, even if the switch happens on different days in different time zones.

The current version is already useful, but it's missing a key feature, the ability to easily choose which time zones to list. Right now, if you're comfortable editing HTML, you can edit the `cities[]` array in the script section to specify time zones. Later, it will be easy select time zones directly in your web browser.

Meridian is open source, licensed under the [MIT License](https://opensource.org/licenses/MIT).
