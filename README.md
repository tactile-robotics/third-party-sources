# Third-party source code

This repository provides the corresponding source code for open-source components that
Tactile Robotics redistributes in binary form in its applications, as required by
those components' licences (for example the GNU Lesser General Public License).

It contains no Tactile Robotics application code. Each release holds the source for
one set of redistributed binaries; the archives are attached to the release, not
committed to the repository.

## Releases

| Release | Product | Components |
|---|---|---|
| `denteach-ffmpeg-n5.1.2` | DenTeach Instructor, DenTeach Student | FFmpeg n5.1.2 (`ffmpeg.exe`, `ffplay.exe`, `ffprobe.exe` and the `av*`/`sw*` DLLs) and every library linked into those binaries; OpenCV's FFmpeg wrapper (`opencv_videoio_ffmpeg4110_64.dll`) |

## What each archive contains

- **Upstream source** for every component, at the exact tag, commit or revision used
  to build the shipped binaries.
- **Build scripts** that produced the binaries, including any patches they apply.
- A **`MANIFEST.md`** listing each component, its origin URL, the pinned revision, its
  licence, and the SHA-256 of each archived file.

## Licences

Each component is licensed under its own terms, included inside its source tree. The
applications also show the licence texts in-app under About > Third-party notices.

## Contact

For questions about this source code, contact Tactile Robotics through the support
address listed in the application's About page.
