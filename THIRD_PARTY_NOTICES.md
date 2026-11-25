# CLAW Third-Party Notices

CLAW 0.0.16 · Windows 11 x64 and website

## Windows application

These entries identify the normal Windows Cargo graph used to build CLAW. Windows production graph entries are included here conservatively because link-time optimization can discard unused code. Build-time macros run during compilation and can contribute generated code. Their executables are outside the installer payload. Copyright statements and license language appear in the accompanying `THIRD_PARTY_LICENSES.txt`. The IDs below connect each package to those texts.

The applicable terms include retention of copyright and license notices. Where a component offers alternatives, its original alternatives are shown. For combined terms, all applicable notices are included. The Windows runtime calls operating system facilities including Windows Imaging Component and DirectX. The Launcher uses the Windows .NET Framework 4.8 runtime. The installer carries no Windows redistributable, graphics driver, Vulkan loader, RenderDoc executable, or separate shader compiler DLL.

Optional MP4 export uses FFmpeg with libx264 supplied separately by the user. CLAW does not bundle FFmpeg or x264. License terms depend on the external build. [FFmpeg licensing](https://ffmpeg.org/legal.html)

## Fonts and installer

Montserrat · The Montserrat.Git Project Authors. The app includes baked glyph data, the Launcher embeds a Montserrat TTF and its OFL, and the site includes local WOFF2 subsets and the OFL. Montserrat is provided under SIL OFL 1.1. The font license governs font copies and derivatives. [Montserrat project](https://github.com/JulietaUla/Montserrat)

Font Awesome Free 7.3.1 · Copyright 2026 Fonticons, Inc. Some CLAW desktop icons are based on Font Awesome Free icons under CC BY 4.0. CLAW rasterized and resized the SVG artwork for its interface and rotated selected glyphs. [Font Awesome Free license](https://fontawesome.com/license/free) · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

Inno Setup 6.7.4 · Jordan Russell and Martijn Laan. CLAW distributes the generated setup and uninstaller. The Inno Setup License is reproduced in the accompanying license text. Upstream copyright and website notices are retained. The build uses LZMA2 compression. [Inno Setup](https://jrsoftware.org/inno-setup)

LZMA/LZMA2 · The Inno Setup decoder wrapper by Jordan Russell and LZMA SDK by Igor Pavlov are published in the public domain. [LZMA SDK](https://www.7-zip.org/sdk.html)

The CLAW Windows installer is made using RemObjects Pascal Script by Carlo Kok and RemObjects Software, LLC. The Inno Setup distribution includes its license, reproduced in the accompanying notice bundle. [RemObjects Pascal Script](https://github.com/remobjects/pascalscript)

The Inno Setup ChaCha20 unit credits the public-domain `chacha20-c` implementation as its starting point. [Original implementation license](https://github.com/Ginurx/chacha20-c/blob/master/LICENSE)

Rust standard library · Rust Project Developers and other copyright holders identified in the Rust 1.99.1 notices. Main terms are MIT OR Apache-2.0 with additional component terms. The accompanying license text reproduces the toolchain’s standard-library copyright listing in plain text.

## Light Lab and website artwork

Blender Studio Human Base Meshes v1.4.1 · CLAW includes reduced, baked CC0 1.0 derivatives by Dan Ulrich and Paul Kotelevets. The two heads are used in the app. The website uses a derivative of the realistic head and shows Light Lab in the workspace demonstration. [Blender asset bundles](https://developer.blender.org/docs/release_notes/4.0/asset_bundles/) · [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/)

The website uses Open Access reproductions from The Metropolitan Museum of Art under CC0 1.0. The Art credits section identifies the works, makers and source records. [The Met Open Access policy](https://www.metmuseum.org/hubs/open-access)

## Windows Cargo components

- `allocator-api2 0.2.21` · MIT OR Apache-2.0 · Windows production graph · Zakarum · R001 LICENSE-APACHE, R002 LICENSE-MIT
- `arrayvec 0.7.8` · MIT OR Apache-2.0 · Windows production graph · bluss · R003 LICENSE-APACHE, R004 LICENSE-MIT
- `ash 0.38.0+1.3.281` · MIT OR Apache-2.0 · Windows production graph · Maik Klein, Benjamin Saunders, Marijn Suijten · R005 LICENSE-APACHE, R006 LICENSE-MIT
- `bit-set 0.10.0` · Apache-2.0 OR MIT · Windows production graph · Alexis Beingessner · R007 LICENSE-APACHE, R008 LICENSE-MIT
- `bit-vec 0.9.1` · Apache-2.0 OR MIT · Windows production graph · Alexis Beingessner · R007 LICENSE-APACHE, R009 LICENSE-MIT
- `bitflags 2.13.2` · MIT OR Apache-2.0 · Windows production graph · The Rust Project Developers · R003 LICENSE-APACHE, R010 LICENSE-MIT
- `bytemuck 1.25.2` · Zlib OR Apache-2.0 OR MIT · Windows production graph · Lokathor · R011 LICENSE-APACHE, R012 LICENSE-MIT, R013 LICENSE-ZLIB
- `bytemuck_derive 1.12.1` · Zlib OR Apache-2.0 OR MIT · Build-time macro · Lokathor · R011 LICENSE-APACHE, R012 LICENSE-MIT, R013 LICENSE-ZLIB
- `cfg-if 1.0.5` · MIT OR Apache-2.0 · Windows production graph · Alex Crichton · R003 LICENSE-APACHE, R014 LICENSE-MIT
- `codespan-reporting 0.13.1` · Apache-2.0 · Windows production graph · Brendan Zabarauskas · R015 LICENSE
- `cursor-icon 1.2.0` · MIT OR Apache-2.0 OR Zlib · Windows production graph · Kirill Chibisov · R016 LICENSE-APACHE, R017 LICENSE-MIT, R018 LICENSE-ZLIB
- `document-features 0.2.12` · MIT OR Apache-2.0 · Build-time macro · Slint Developers · R019 LICENSE-APACHE, R020 LICENSE-MIT
- `dpi 0.1.2` · Apache-2.0 AND MIT · Windows production graph · R021 LICENSE, R022 LICENSE-LIBM-MIT
- `equivalent 1.0.3` · Apache-2.0 OR MIT · Windows production graph · R003 LICENSE-APACHE, R023 LICENSE-MIT
- `foldhash 0.2.0` · Zlib · Windows production graph · Orson Peters · R024 LICENSE
- `getrandom 0.4.3` · MIT OR Apache-2.0 · Windows production graph · The Rand Project Developers · R025 LICENSE-APACHE, R026 LICENSE-MIT
- `gpu-allocator 0.28.0` · MIT OR Apache-2.0 · Windows production graph · Traverse Research · R027 LICENSE-APACHE, R028 LICENSE-MIT
- `half 2.7.1` · MIT OR Apache-2.0 · Windows production graph · Kathryn Long · R029 LICENSE-APACHE, R030 LICENSE-MIT
- `hashbrown 0.16.1` · MIT OR Apache-2.0 · Windows production graph · Amanieu d'Antras · R003 LICENSE-APACHE, R031 LICENSE-MIT
- `hashbrown 0.17.1` · MIT OR Apache-2.0 · Windows production graph · R003 LICENSE-APACHE, R031 LICENSE-MIT
- `indexmap 2.14.2` · Apache-2.0 OR MIT · Windows production graph · R003 LICENSE-APACHE, R032 LICENSE-MIT
- `libloading 0.8.9` · ISC · Windows production graph · Simonas Kazlauskas · R033 LICENSE
- `libm 0.2.16` · MIT · Windows production graph · Alex Crichton, Amanieu d'Antras, Jorge Aparicio, Trevor Gross · R034 LICENSE.txt
- `litrs 1.0.1` · MIT OR Apache-2.0 · Windows production graph · Lukas Kalbertodt · R035 LICENSE-APACHE, R036 LICENSE-MIT
- `lock_api 0.4.14` · MIT OR Apache-2.0 · Windows production graph · Amanieu d'Antras · R003 LICENSE-APACHE, R037 LICENSE-MIT
- `log 0.4.35` · MIT OR Apache-2.0 · Windows production graph · The Rust Project Developers · R003 LICENSE-APACHE, R010 LICENSE-MIT
- `naga 30.0.1` · MIT OR Apache-2.0 · Windows production graph · gfx-rs developers · R029 LICENSE.APACHE, R038 LICENSE.MIT
- `naga-types 30.0.1` · MIT OR Apache-2.0 · Windows production graph · gfx-rs developers · R029 LICENSE.APACHE, R038 LICENSE.MIT
- `num-traits 0.2.19` · MIT OR Apache-2.0 · Windows production graph · The Rust Project Developers · R003 LICENSE-APACHE, R010 LICENSE-MIT
- `once_cell 1.21.4` · MIT OR Apache-2.0 · Windows production graph · Aleksey Kladov · R003 LICENSE-APACHE, R039 LICENSE-MIT
- `ordered-float 5.5.1` · MIT · Windows production graph · Jonathan Reem, Matt Brubeck · R040 LICENSE-MIT
- `parking_lot 0.12.5` · MIT OR Apache-2.0 · Windows production graph · Amanieu d'Antras · R003 LICENSE-APACHE, R037 LICENSE-MIT
- `parking_lot_core 0.9.12` · MIT OR Apache-2.0 · Windows production graph · Amanieu d'Antras · R003 LICENSE-APACHE, R037 LICENSE-MIT
- `pin-project-lite 0.2.17` · Apache-2.0 OR MIT · Windows production graph · R041 LICENSE-APACHE, R039 LICENSE-MIT
- `pollster 1.0.1` · Apache-2.0 OR MIT · Windows production graph · Joshua Barretto · R003 LICENSE-APACHE, R042 LICENSE-MIT
- `presser 0.3.1` · MIT OR Apache-2.0 · Windows production graph · Embark, Gray Olson · R007 LICENSE-APACHE, R043 LICENSE-MIT
- `proc-macro2 1.0.107` · MIT OR Apache-2.0 · Windows production graph · David Tolnay, Alex Crichton · R035 LICENSE-APACHE, R039 LICENSE-MIT
- `profiling 1.0.18` · MIT OR Apache-2.0 · Windows production graph · Philip Degarmo · R044 profiling-LICENSE-APACHE.txt, R045 profiling-LICENSE-MIT.txt
- `quote 1.0.47` · MIT OR Apache-2.0 · Windows production graph · David Tolnay · R035 LICENSE-APACHE, R039 LICENSE-MIT
- `range-alloc 0.1.5` · MIT OR Apache-2.0 · Windows production graph · the gfx-rs Developers · R029 LICENSE.APACHE, R046 LICENSE.MIT
- `raw-window-handle 0.6.2` · MIT OR Apache-2.0 OR Zlib · Windows production graph · Osspial · R041 LICENSE-APACHE.md, R047 LICENSE-MIT.md, R048 LICENSE-ZLIB.md
- `renderdoc-sys 1.1.0` · MIT OR Apache-2.0 · Windows production graph · Eyal Kalderon · R003 LICENSE-APACHE, R049 LICENSE-MIT
- `rustc-hash 1.1.0` · Apache-2.0 OR MIT · Windows production graph · The Rust Project Developers · R003 LICENSE-APACHE, R039 LICENSE-MIT
- `scopeguard 1.2.0` · MIT OR Apache-2.0 · Windows production graph · bluss · R003 LICENSE-APACHE, R050 LICENSE-MIT
- `smallvec 1.16.4` · MIT OR Apache-2.0 · Windows production graph · The Servo Project Developers · R003 LICENSE-APACHE, R051 LICENSE-MIT
- `smol_str 0.2.2` · MIT OR Apache-2.0 · Windows production graph · Aleksey Kladov · R003 LICENSE-APACHE, R039 LICENSE-MIT
- `spirv 0.4.0+sdk-1.4.341.0` · Apache-2.0 · Windows production graph · Lei Zhang · R052 spirv-LICENSE.txt
- `static_assertions 1.1.0` · MIT OR Apache-2.0 · Windows production graph · Nikolai Vazquez · R052 LICENSE-APACHE, R053 LICENSE-MIT
- `syn 2.0.119` · MIT OR Apache-2.0 · Windows production graph · David Tolnay · R035 LICENSE-APACHE, R039 LICENSE-MIT
- `syn 3.0.9` · MIT OR Apache-2.0 · Windows production graph · David Tolnay · R035 LICENSE-APACHE, R039 LICENSE-MIT
- `thiserror 2.0.21` · MIT OR Apache-2.0 · Windows production graph · David Tolnay · R035 LICENSE-APACHE, R039 LICENSE-MIT
- `thiserror-impl 2.0.21` · MIT OR Apache-2.0 · Build-time macro · David Tolnay · R035 LICENSE-APACHE, R039 LICENSE-MIT
- `tracing 0.1.44` · MIT · Windows production graph · Eliza Weisman, Tokio Contributors · R054 LICENSE
- `tracing-core 0.1.36` · MIT · Windows production graph · Tokio Contributors · R054 LICENSE
- `unicode-ident 1.0.27` · (MIT OR Apache-2.0) AND Unicode-3.0 · Windows production graph · David Tolnay · R035 LICENSE-APACHE, R039 LICENSE-MIT, R055 LICENSE-UNICODE
- `unicode-segmentation 1.13.3` · MIT OR Apache-2.0 · Windows production graph · kwantam, Manish Goregaokar · R056 COPYRIGHT, R003 LICENSE-APACHE, R057 LICENSE-MIT
- `unicode-width 0.2.3` · MIT OR Apache-2.0 · Windows production graph · kwantam, Manish Goregaokar · R056 COPYRIGHT, R003 LICENSE-APACHE, R057 LICENSE-MIT
- `wgpu 30.0.1` · MIT OR Apache-2.0 · Windows production graph · gfx-rs developers · R029 LICENSE.APACHE, R038 LICENSE.MIT
- `wgpu-core 30.0.1` · MIT OR Apache-2.0 · Windows production graph · gfx-rs developers · R029 LICENSE.APACHE, R038 LICENSE.MIT
- `wgpu-core-deps-windows-linux-android 30.0.1` · MIT OR Apache-2.0 · Windows production graph · gfx-rs developers · R029 LICENSE.APACHE, R038 LICENSE.MIT
- `wgpu-hal 30.0.1` · MIT OR Apache-2.0 · Windows production graph · gfx-rs developers · R029 LICENSE.APACHE, R038 LICENSE.MIT
- `wgpu-naga-bridge 30.0.1` · MIT OR Apache-2.0 · Windows production graph · gfx-rs developers · R029 LICENSE.APACHE, R038 LICENSE.MIT
- `wgpu-types 30.0.1` · MIT OR Apache-2.0 · Windows production graph · gfx-rs developers · R029 LICENSE.APACHE, R038 LICENSE.MIT
- `windows 0.62.2` · MIT OR Apache-2.0 · Windows production graph · R058 license-apache-2.0, R059 license-mit
- `windows_x86_64_msvc 0.52.6` · MIT OR Apache-2.0 · Windows production graph · Microsoft · R058 license-apache-2.0, R059 license-mit
- `windows-collections 0.3.2` · MIT OR Apache-2.0 · Windows production graph · R058 license-apache-2.0, R059 license-mit
- `windows-core 0.62.2` · MIT OR Apache-2.0 · Windows production graph · R058 license-apache-2.0, R059 license-mit
- `windows-future 0.3.2` · MIT OR Apache-2.0 · Windows production graph · R058 license-apache-2.0, R059 license-mit
- `windows-implement 0.60.2` · MIT OR Apache-2.0 · Build-time macro · R058 license-apache-2.0, R059 license-mit
- `windows-interface 0.59.3` · MIT OR Apache-2.0 · Build-time macro · R058 license-apache-2.0, R059 license-mit
- `windows-link 0.2.1` · MIT OR Apache-2.0 · Windows production graph · R058 license-apache-2.0, R059 license-mit
- `windows-numerics 0.3.1` · MIT OR Apache-2.0 · Windows production graph · R058 license-apache-2.0, R059 license-mit
- `windows-result 0.4.1` · MIT OR Apache-2.0 · Windows production graph · R058 license-apache-2.0, R059 license-mit
- `windows-strings 0.5.1` · MIT OR Apache-2.0 · Windows production graph · R058 license-apache-2.0, R059 license-mit
- `windows-sys 0.52.0` · MIT OR Apache-2.0 · Windows production graph · Microsoft · R058 license-apache-2.0, R059 license-mit
- `windows-sys 0.61.2` · MIT OR Apache-2.0 · Windows production graph · R058 license-apache-2.0, R059 license-mit
- `windows-targets 0.52.6` · MIT OR Apache-2.0 · Windows production graph · Microsoft · R058 license-apache-2.0, R059 license-mit
- `windows-threading 0.2.1` · MIT OR Apache-2.0 · Windows production graph · R058 license-apache-2.0, R059 license-mit
- `winit 0.30.13` · Apache-2.0 · Windows production graph · The winit contributors, Pierre Krieger · R021 LICENSE
- `zerocopy 0.8.63` · BSD-2-Clause OR Apache-2.0 OR MIT · Windows production graph · R060 LICENSE-APACHE, R061 LICENSE-BSD, R062 LICENSE-MIT
- `zerocopy-derive 0.8.63` · BSD-2-Clause OR Apache-2.0 OR MIT · Build-time macro · R060 LICENSE-APACHE, R061 LICENSE-BSD, R062 LICENSE-MIT
