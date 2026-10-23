# Native theme media

Images, fonts, videos, and interface sounds used by ThemeHub native themes. The code and renderers remain in Kaal31/benderthemes; these files are delivered through immutable release packs.

`manifest.json` records each pack version, release URL, archive checksum, and extracted file checksum. Existing releases are retained. Old Big Picture and Old Beta Big Picture share the Old Big Picture image and UI sound pack. Original Valve artwork and sounds retain their original ownership; theme code credits are in the plugin repository.

Old Big Picture media v1.0.2 also includes the original 1080p Big Picture startup clip used by both dashboards. `old-big-picture/intro-source.json` records the user-provided Rybz video title, duration and original file checksum. The video bytes are preserved unchanged.

Floating Castle v1.0.3, Republic v1.0.3 and Nazarick v1.0.4 add VP9/WebM compatibility backgrounds. These are 1280×720 encodings of the original published MP4 movies, with the unused audio and attached thumbnail stream omitted. The original MP4s and other pack contents remain in their immutable releases. `manifest.json` records the compatibility file hashes and their new pack checksums.
