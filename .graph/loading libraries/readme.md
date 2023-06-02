# Try:
- https://github.com/ptitSeb/box86/issues/614
- https://pyra-handheld.com/boards/threads/box86-error-loading-libs-on-rasp-4.99633/

sch: https://www.google.com/search?q=box86+%22libcap.%22+so.2


cause:
>Yes. Not all libs gets wrapped. Like wine, it's a manual process. So many libs are wrapped, but some are not. Like this libappindicator3. So you need an i686 version, from some rpm or deb or somewhere else yes. Put it in the app folder and box86 will find it, no need to use LD_ env. var.
