load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "io_bazel_rules_docker",
    sha256 = "4521794f0fba2e20f3bf15846ab5e01d5332e587e9ce81629c7f96c793bb7036",
    strip_prefix = "rules_docker-0.14.4",
    urls = ["https://github.com/bazelbuild/rules_docker/releases/download/v0.14.4/rules_docker-v0.14.4.tar.gz"],
)

load(
    "@io_bazel_rules_docker//repositories:repositories.bzl",
    container_repositories = "repositories",
)

container_repositories()

load("@io_bazel_rules_docker//repositories:deps.bzl", container_deps = "deps")

container_deps()

load("@io_bazel_rules_docker//repositories:pip_repositories.bzl", "pip_deps")

pip_deps()

load(
    "@io_bazel_rules_docker//container:container.bzl",
    "container_pull",
)

container_pull(
    name = "debian_base",
    digest = "sha256:e7157902df9c7549eea5eb7b896cdca02d917e2ba0e339cd4a5087e2b53eb1d7",
    registry = "docker.io",
    repository = "debian",
)

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_file")

http_file(
    name = "adwaita-icon-theme_3.22.0-1_deb9u1_all_deb",
    downloaded_file_path = "adwaita-icon-theme_3.22.0-1+deb9u1_all.deb",
    sha256 = "9f956279c715b657f590370751ee91e74376fe06b18cf35a05930b13bb1737a6",
    urls = ["http://deb.debian.org/debian/pool/main/a/adwaita-icon-theme/adwaita-icon-theme_3.22.0-1+deb9u1_all.deb"],
)

http_file(
    name = "at-spi2-core_2.22.0-6_deb9u1_amd64_deb",
    downloaded_file_path = "at-spi2-core_2.22.0-6+deb9u1_amd64.deb",
    sha256 = "36aad01ab9485e236fb1f7df547341495d6988b8053709a1deffbc3aca9525a3",
    urls = ["http://deb.debian.org/debian/pool/main/a/at-spi2-core/at-spi2-core_2.22.0-6+deb9u1_amd64.deb"],
)

http_file(
    name = "ca-certificates_20200601_deb9u1_all_deb",
    downloaded_file_path = "ca-certificates_20200601~deb9u1_all.deb",
    sha256 = "d6fc9275de84bdf598b3703a50935dc69d2e80105317a44f6cba465c073f88f9",
    urls = ["http://deb.debian.org/debian/pool/main/c/ca-certificates/ca-certificates_20200601~deb9u1_all.deb"],
)

http_file(
    name = "ca-certificates-java_20170929_deb9u3_all_deb",
    downloaded_file_path = "ca-certificates-java_20170929~deb9u3_all.deb",
    sha256 = "735ca819679981197b705c54c6ab0321308ebd8038256fe863875e46f26c2d64",
    urls = ["http://deb.debian.org/debian/pool/main/c/ca-certificates-java/ca-certificates-java_20170929~deb9u3_all.deb"],
)

http_file(
    name = "dbus_1.10.32-0_deb9u1_amd64_deb",
    downloaded_file_path = "dbus_1.10.32-0+deb9u1_amd64.deb",
    sha256 = "53b4d8ac5c4bfc44800736c13de6adb9312e7400943b13cdffc90e271af5dbd9",
    urls = ["http://deb.debian.org/debian/pool/main/d/dbus/dbus_1.10.32-0+deb9u1_amd64.deb"],
)

http_file(
    name = "dconf-gsettings-backend_0.26.0-2_b1_amd64_deb",
    downloaded_file_path = "dconf-gsettings-backend_0.26.0-2+b1_amd64.deb",
    sha256 = "e9916b90f7d073b9048c3cbd584f7149b738d4c2ffa3842635b9bc60b42aae20",
    urls = ["http://deb.debian.org/debian/pool/main/d/d-conf/dconf-gsettings-backend_0.26.0-2+b1_amd64.deb"],
)

http_file(
    name = "dconf-service_0.26.0-2_b1_amd64_deb",
    downloaded_file_path = "dconf-service_0.26.0-2+b1_amd64.deb",
    sha256 = "d1f1a8395c6d6b9deebf5f37f28169e21105f73d9d40c46c20a476227faf8c3b",
    urls = ["http://deb.debian.org/debian/pool/main/d/d-conf/dconf-service_0.26.0-2+b1_amd64.deb"],
)

http_file(
    name = "fontconfig_2.11.0-6.7_b1_amd64_deb",
    downloaded_file_path = "fontconfig_2.11.0-6.7+b1_amd64.deb",
    sha256 = "6976c5e1b690c9c92f55a1c53f57094fdb86e619481d2e903561436cc2235b73",
    urls = ["http://deb.debian.org/debian/pool/main/f/fontconfig/fontconfig_2.11.0-6.7+b1_amd64.deb"],
)

http_file(
    name = "fontconfig-config_2.11.0-6.7_all_deb",
    downloaded_file_path = "fontconfig-config_2.11.0-6.7_all.deb",
    sha256 = "8226e3a525fef6aee3268929d15ed8352a7edfa263b8f70e3eb1a0962e772e27",
    urls = ["http://deb.debian.org/debian/pool/main/f/fontconfig/fontconfig-config_2.11.0-6.7_all.deb"],
)

http_file(
    name = "fonts-dejavu-core_2.37-1_all_deb",
    downloaded_file_path = "fonts-dejavu-core_2.37-1_all.deb",
    sha256 = "58d21a255606191e6512cca51f32c4480e7a798945cc980623377696acfa3cfc",
    urls = ["http://deb.debian.org/debian/pool/main/f/fonts-dejavu/fonts-dejavu-core_2.37-1_all.deb"],
)

http_file(
    name = "fonts-dejavu-extra_2.37-1_all_deb",
    downloaded_file_path = "fonts-dejavu-extra_2.37-1_all.deb",
    sha256 = "2e32c98aea163c0b0bd85b44a464b1bfe8304131e3b2440bf2cf4b2ff78eb372",
    urls = ["http://deb.debian.org/debian/pool/main/f/fonts-dejavu/fonts-dejavu-extra_2.37-1_all.deb"],
)

http_file(
    name = "glib-networking_2.50.0-1_deb9u1_amd64_deb",
    downloaded_file_path = "glib-networking_2.50.0-1+deb9u1_amd64.deb",
    sha256 = "3484eb1c4e2a010c8d2f66342781b1fdf7daaa695b1ebe74242056f442cd8fe7",
    urls = ["http://deb.debian.org/debian/pool/main/g/glib-networking/glib-networking_2.50.0-1+deb9u1_amd64.deb"],
)

http_file(
    name = "glib-networking-common_2.50.0-1_deb9u1_all_deb",
    downloaded_file_path = "glib-networking-common_2.50.0-1+deb9u1_all.deb",
    sha256 = "9431fa7297572f00a415e778d2479a1909e0017c4261ea55f5bf38d53b911dcf",
    urls = ["http://deb.debian.org/debian/pool/main/g/glib-networking/glib-networking-common_2.50.0-1+deb9u1_all.deb"],
)

http_file(
    name = "glib-networking-services_2.50.0-1_deb9u1_amd64_deb",
    downloaded_file_path = "glib-networking-services_2.50.0-1+deb9u1_amd64.deb",
    sha256 = "7badd67fbc54493d20ff011f5874f25b952fa6fc40775b1130c6f15d90862b04",
    urls = ["http://deb.debian.org/debian/pool/main/g/glib-networking/glib-networking-services_2.50.0-1+deb9u1_amd64.deb"],
)

http_file(
    name = "gnome-icon-theme_3.12.0-2_all_deb",
    downloaded_file_path = "gnome-icon-theme_3.12.0-2_all.deb",
    sha256 = "6f918206118943badc16751bc682ce764223652bf5d70b7683b680235a585788",
    urls = ["http://deb.debian.org/debian/pool/main/g/gnome-icon-theme/gnome-icon-theme_3.12.0-2_all.deb"],
)

http_file(
    name = "gsettings-desktop-schemas_3.22.0-1_all_deb",
    downloaded_file_path = "gsettings-desktop-schemas_3.22.0-1_all.deb",
    sha256 = "bdce8c517bc656c7b621e4c866149f142a9e52cce80f91cf8b07e2332d204589",
    urls = ["http://deb.debian.org/debian/pool/main/g/gsettings-desktop-schemas/gsettings-desktop-schemas_3.22.0-1_all.deb"],
)

http_file(
    name = "gtk-update-icon-cache_3.22.11-1_amd64_deb",
    downloaded_file_path = "gtk-update-icon-cache_3.22.11-1_amd64.deb",
    sha256 = "efb1b77e02a201a7e5bc3474bb2dbedb707de0bd734482a7f8d5df4579c5913a",
    urls = ["http://deb.debian.org/debian/pool/main/g/gtk+3.0/gtk-update-icon-cache_3.22.11-1_amd64.deb"],
)

http_file(
    name = "hicolor-icon-theme_0.15-1_all_deb",
    downloaded_file_path = "hicolor-icon-theme_0.15-1_all.deb",
    sha256 = "ccad1133347b30513230c896e0072f58910affbbc8947e084d482bef6c5eea00",
    urls = ["http://deb.debian.org/debian/pool/main/h/hicolor-icon-theme/hicolor-icon-theme_0.15-1_all.deb"],
)

http_file(
    name = "java-common_0.58_deb9u1_all_deb",
    downloaded_file_path = "java-common_0.58+deb9u1_all.deb",
    sha256 = "ceee63ee76d04af5d95785a4586cd621ad9cbf6a87ee54c7e163c6d1434c4765",
    urls = ["http://deb.debian.org/debian/pool/main/j/java-common/java-common_0.58+deb9u1_all.deb"],
)

http_file(
    name = "krb5-locales_1.15-1_deb9u1_all_deb",
    downloaded_file_path = "krb5-locales_1.15-1+deb9u1_all.deb",
    sha256 = "fe842c167661789bf22ffb5842dad6614dac453f6b62b4a54134845498fbf45b",
    urls = ["http://deb.debian.org/debian/pool/main/k/krb5/krb5-locales_1.15-1+deb9u1_all.deb"],
)

http_file(
    name = "libapparmor1_2.11.0-3_deb9u2_amd64_deb",
    downloaded_file_path = "libapparmor1_2.11.0-3+deb9u2_amd64.deb",
    sha256 = "0bb82877e45957b4d9cd20c6f92a3a1201d8b4f8ee737b2ddc42006ba4da4ee9",
    urls = ["http://deb.debian.org/debian/pool/main/a/apparmor/libapparmor1_2.11.0-3+deb9u2_amd64.deb"],
)

http_file(
    name = "libasound2_1.1.3-5_amd64_deb",
    downloaded_file_path = "libasound2_1.1.3-5_amd64.deb",
    sha256 = "12c543d7e6f6856983e654d0465622c8aee44d0024339d7b563c7f99c249c9d7",
    urls = ["http://deb.debian.org/debian/pool/main/a/alsa-lib/libasound2_1.1.3-5_amd64.deb"],
)

http_file(
    name = "libasound2-data_1.1.3-5_all_deb",
    downloaded_file_path = "libasound2-data_1.1.3-5_all.deb",
    sha256 = "c142334973c123450b25acd1432742db37994498b38849d87ffe086d8d173ea9",
    urls = ["http://deb.debian.org/debian/pool/main/a/alsa-lib/libasound2-data_1.1.3-5_all.deb"],
)

http_file(
    name = "libasyncns0_0.8-6_amd64_deb",
    downloaded_file_path = "libasyncns0_0.8-6_amd64.deb",
    sha256 = "64208642c23b846ccc421b22c3c610f4482e25ebb6b2a294dc8c79fdfc333294",
    urls = ["http://deb.debian.org/debian/pool/main/liba/libasyncns/libasyncns0_0.8-6_amd64.deb"],
)

http_file(
    name = "libatk1.0-0_2.22.0-1_amd64_deb",
    downloaded_file_path = "libatk1.0-0_2.22.0-1_amd64.deb",
    sha256 = "dd714b9581b5f6dcb4fe711285117b6a63fa03bd40ad7adad28838883f60236d",
    urls = ["http://deb.debian.org/debian/pool/main/a/atk1.0/libatk1.0-0_2.22.0-1_amd64.deb"],
)

http_file(
    name = "libatk1.0-data_2.22.0-1_all_deb",
    downloaded_file_path = "libatk1.0-data_2.22.0-1_all.deb",
    sha256 = "e48623184d071483e69d1c02dd0163f9a439b9e11c46628ebd230851b2625b1c",
    urls = ["http://deb.debian.org/debian/pool/main/a/atk1.0/libatk1.0-data_2.22.0-1_all.deb"],
)

http_file(
    name = "libatk-bridge2.0-0_2.22.0-2_amd64_deb",
    downloaded_file_path = "libatk-bridge2.0-0_2.22.0-2_amd64.deb",
    sha256 = "b1c244aabf51f1175276680b67360f59268f4bd8732b9315d353c754caa6fa85",
    urls = ["http://deb.debian.org/debian/pool/main/a/at-spi2-atk/libatk-bridge2.0-0_2.22.0-2_amd64.deb"],
)

http_file(
    name = "libatk-wrapper-java_0.33.3-13_deb9u1_all_deb",
    downloaded_file_path = "libatk-wrapper-java_0.33.3-13+deb9u1_all.deb",
    sha256 = "402f4d4ffc2f84c7a1fc90f775fdd9756677fcad9770bc4d03f4824c9789efb0",
    urls = ["http://deb.debian.org/debian/pool/main/j/java-atk-wrapper/libatk-wrapper-java_0.33.3-13+deb9u1_all.deb"],
)

http_file(
    name = "libatk-wrapper-java-jni_0.33.3-13_deb9u1_amd64_deb",
    downloaded_file_path = "libatk-wrapper-java-jni_0.33.3-13+deb9u1_amd64.deb",
    sha256 = "57ac13283d86e13c8810e2a22fba148cea014e99f08ab43f4e474cae3a441e0f",
    urls = ["http://deb.debian.org/debian/pool/main/j/java-atk-wrapper/libatk-wrapper-java-jni_0.33.3-13+deb9u1_amd64.deb"],
)

http_file(
    name = "libatspi2.0-0_2.22.0-6_deb9u1_amd64_deb",
    downloaded_file_path = "libatspi2.0-0_2.22.0-6+deb9u1_amd64.deb",
    sha256 = "b82764593e5ae25098ffcaf01eda8c32fe2ac55c0e532f4d19ad1405516b57e0",
    urls = ["http://deb.debian.org/debian/pool/main/a/at-spi2-core/libatspi2.0-0_2.22.0-6+deb9u1_amd64.deb"],
)

http_file(
    name = "libavahi-client3_0.6.32-2_amd64_deb",
    downloaded_file_path = "libavahi-client3_0.6.32-2_amd64.deb",
    sha256 = "2a3f8117706ef5c82efa099232251a5ccf4b0fe38ffb00ab75153e0685a79436",
    urls = ["http://deb.debian.org/debian/pool/main/a/avahi/libavahi-client3_0.6.32-2_amd64.deb"],
)

http_file(
    name = "libavahi-common3_0.6.32-2_amd64_deb",
    downloaded_file_path = "libavahi-common3_0.6.32-2_amd64.deb",
    sha256 = "eacb7a9afa0652babf3fea28de654ef130a73a3b5e6164e488f182a07139e0b5",
    urls = ["http://deb.debian.org/debian/pool/main/a/avahi/libavahi-common3_0.6.32-2_amd64.deb"],
)

http_file(
    name = "libavahi-common-data_0.6.32-2_amd64_deb",
    downloaded_file_path = "libavahi-common-data_0.6.32-2_amd64.deb",
    sha256 = "2ce20408664c015a2013f29597131e1e983c33cd17ea82ca248c1644b9d04a44",
    urls = ["http://deb.debian.org/debian/pool/main/a/avahi/libavahi-common-data_0.6.32-2_amd64.deb"],
)

http_file(
    name = "libbsd0_0.8.3-1_amd64_deb",
    downloaded_file_path = "libbsd0_0.8.3-1_amd64.deb",
    sha256 = "030e441cc6368041536a69adcaed6b4f4a37e0145817fc3eff16f37e3a81ecae",
    urls = ["http://deb.debian.org/debian/pool/main/libb/libbsd/libbsd0_0.8.3-1_amd64.deb"],
)

http_file(
    name = "libcairo2_1.14.8-1_amd64_deb",
    downloaded_file_path = "libcairo2_1.14.8-1_amd64.deb",
    sha256 = "1f6ebf5f89c05c2e4aae96343f41446e2a847a3686c1dd22db39922df1e60f73",
    urls = ["http://deb.debian.org/debian/pool/main/c/cairo/libcairo2_1.14.8-1_amd64.deb"],
)

http_file(
    name = "libcairo-gobject2_1.14.8-1_amd64_deb",
    downloaded_file_path = "libcairo-gobject2_1.14.8-1_amd64.deb",
    sha256 = "1001a84a8a4ce73cb75f8473cc86fff6944745cd1fcbfa5eb858465b8fc8e9bf",
    urls = ["http://deb.debian.org/debian/pool/main/c/cairo/libcairo-gobject2_1.14.8-1_amd64.deb"],
)

http_file(
    name = "libcolord2_1.3.3-2_amd64_deb",
    downloaded_file_path = "libcolord2_1.3.3-2_amd64.deb",
    sha256 = "0f6d8479a3cf3006f882508be0ddd75d957585a2cc5583867655e480a0850bbd",
    urls = ["http://deb.debian.org/debian/pool/main/c/colord/libcolord2_1.3.3-2_amd64.deb"],
)

http_file(
    name = "libcroco3_0.6.11-3_amd64_deb",
    downloaded_file_path = "libcroco3_0.6.11-3_amd64.deb",
    sha256 = "3a1e1af6a81c04035d67c1928460270448ac5ae30b79f68cd1c2acabb77debf8",
    urls = ["http://deb.debian.org/debian/pool/main/libc/libcroco/libcroco3_0.6.11-3_amd64.deb"],
)

http_file(
    name = "libcups2_2.2.1-8_deb9u6_amd64_deb",
    downloaded_file_path = "libcups2_2.2.1-8+deb9u6_amd64.deb",
    sha256 = "75f7dac879b18164e322fbf16211bffc6c5c09ca5884adf177ff6e3d69e2fc0a",
    urls = ["http://deb.debian.org/debian/pool/main/c/cups/libcups2_2.2.1-8+deb9u6_amd64.deb"],
)

http_file(
    name = "libdatrie1_0.2.10-4_b1_amd64_deb",
    downloaded_file_path = "libdatrie1_0.2.10-4+b1_amd64.deb",
    sha256 = "07349230986b454db6cec4f20fd648235e89f5a7ba258371e5da1dd7ba3992c9",
    urls = ["http://deb.debian.org/debian/pool/main/libd/libdatrie/libdatrie1_0.2.10-4+b1_amd64.deb"],
)

http_file(
    name = "libdbus-1-3_1.10.32-0_deb9u1_amd64_deb",
    downloaded_file_path = "libdbus-1-3_1.10.32-0+deb9u1_amd64.deb",
    sha256 = "55a360fd6529f7d42a1c13ddf53c977b3b854d065e8fcc3f482a3faf65e9a20f",
    urls = ["http://deb.debian.org/debian/pool/main/d/dbus/libdbus-1-3_1.10.32-0+deb9u1_amd64.deb"],
)

http_file(
    name = "libdconf1_0.26.0-2_b1_amd64_deb",
    downloaded_file_path = "libdconf1_0.26.0-2+b1_amd64.deb",
    sha256 = "2574fbcaef168f864033c2a4cdf5d0355da0a89720f28a015e30e445838a9ea0",
    urls = ["http://deb.debian.org/debian/pool/main/d/d-conf/libdconf1_0.26.0-2+b1_amd64.deb"],
)

http_file(
    name = "libdrm2_2.4.74-1_amd64_deb",
    downloaded_file_path = "libdrm2_2.4.74-1_amd64.deb",
    sha256 = "c3f893782dc905fdc267f70c38488bee0211a5c501876fdfcdfc46941a75b553",
    urls = ["http://deb.debian.org/debian/pool/main/libd/libdrm/libdrm2_2.4.74-1_amd64.deb"],
)

http_file(
    name = "libdrm-amdgpu1_2.4.74-1_amd64_deb",
    downloaded_file_path = "libdrm-amdgpu1_2.4.74-1_amd64.deb",
    sha256 = "a61e98408584a8454b239e6fe85ee2f010d3e2a4ac60242756b9d1616599b0a6",
    urls = ["http://deb.debian.org/debian/pool/main/libd/libdrm/libdrm-amdgpu1_2.4.74-1_amd64.deb"],
)

http_file(
    name = "libdrm-intel1_2.4.74-1_amd64_deb",
    downloaded_file_path = "libdrm-intel1_2.4.74-1_amd64.deb",
    sha256 = "045504f526cbbbca66fa2bbb29ee79a645109db259fb62d904e70b93d759095c",
    urls = ["http://deb.debian.org/debian/pool/main/libd/libdrm/libdrm-intel1_2.4.74-1_amd64.deb"],
)

http_file(
    name = "libdrm-nouveau2_2.4.74-1_amd64_deb",
    downloaded_file_path = "libdrm-nouveau2_2.4.74-1_amd64.deb",
    sha256 = "9017e7cfa7608527bd3475d9401fc0e47710444d7bda07f67b043414825954f7",
    urls = ["http://deb.debian.org/debian/pool/main/libd/libdrm/libdrm-nouveau2_2.4.74-1_amd64.deb"],
)

http_file(
    name = "libdrm-radeon1_2.4.74-1_amd64_deb",
    downloaded_file_path = "libdrm-radeon1_2.4.74-1_amd64.deb",
    sha256 = "2cfb9c4ad8cfaaa7e8460ca013953ebb0d71d90487814505a58203dece6551dd",
    urls = ["http://deb.debian.org/debian/pool/main/libd/libdrm/libdrm-radeon1_2.4.74-1_amd64.deb"],
)

http_file(
    name = "libedit2_3.1-20160903-3_amd64_deb",
    downloaded_file_path = "libedit2_3.1-20160903-3_amd64.deb",
    sha256 = "658cc7ea0e123302c382c7273991427b6b5709b0bb19a5a0f08e78ea3d5d2aab",
    urls = ["http://deb.debian.org/debian/pool/main/libe/libedit/libedit2_3.1-20160903-3_amd64.deb"],
)

http_file(
    name = "libegl1-mesa_13.0.6-1_b2_amd64_deb",
    downloaded_file_path = "libegl1-mesa_13.0.6-1+b2_amd64.deb",
    sha256 = "7809a6cfeb82b4c136a8720170a44525da45eb369cb0282d304fc8b305685d83",
    urls = ["http://deb.debian.org/debian/pool/main/m/mesa/libegl1-mesa_13.0.6-1+b2_amd64.deb"],
)

http_file(
    name = "libepoxy0_1.3.1-2_amd64_deb",
    downloaded_file_path = "libepoxy0_1.3.1-2_amd64.deb",
    sha256 = "06bea134777e7160b9ad7eadd126525ca79525cea8ad2a49e7229e4e328b8ad3",
    urls = ["http://deb.debian.org/debian/pool/main/libe/libepoxy/libepoxy0_1.3.1-2_amd64.deb"],
)

http_file(
    name = "libexpat1_2.2.0-2_deb9u3_amd64_deb",
    downloaded_file_path = "libexpat1_2.2.0-2+deb9u3_amd64.deb",
    sha256 = "12857a50ede17ec9957b7cdb04a80dbb603df567501af3aef8ee53932a015cb8",
    urls = ["http://deb.debian.org/debian/pool/main/e/expat/libexpat1_2.2.0-2+deb9u3_amd64.deb"],
)

http_file(
    name = "libffi6_3.2.1-6_amd64_deb",
    downloaded_file_path = "libffi6_3.2.1-6_amd64.deb",
    sha256 = "a385cd7ce2cc6c73e271c4692d4c152d96d6c9ad756c3a36bf503f9c2a462de4",
    urls = ["http://deb.debian.org/debian/pool/main/libf/libffi/libffi6_3.2.1-6_amd64.deb"],
)

http_file(
    name = "libflac8_1.3.2-1_amd64_deb",
    downloaded_file_path = "libflac8_1.3.2-1_amd64.deb",
    sha256 = "2ff0d9cfc39143afa412de17fd9feeaab9e69210f9d19bef94fa34c69a064893",
    urls = ["http://deb.debian.org/debian/pool/main/f/flac/libflac8_1.3.2-1_amd64.deb"],
)

http_file(
    name = "libfontconfig1_2.11.0-6.7_b1_amd64_deb",
    downloaded_file_path = "libfontconfig1_2.11.0-6.7+b1_amd64.deb",
    sha256 = "8e4ac54fe770ff84c4b596e5e66dacc94efad08940fa354a8c112db06c67d588",
    urls = ["http://deb.debian.org/debian/pool/main/f/fontconfig/libfontconfig1_2.11.0-6.7+b1_amd64.deb"],
)

http_file(
    name = "libfontenc1_1.1.3-1_b2_amd64_deb",
    downloaded_file_path = "libfontenc1_1.1.3-1+b2_amd64.deb",
    sha256 = "f456b6168c57c41bfd0bd04d7dfb445c283372585e87333e8de42eebdc92366e",
    urls = ["http://deb.debian.org/debian/pool/main/libf/libfontenc/libfontenc1_1.1.3-1+b2_amd64.deb"],
)

http_file(
    name = "libfreetype6_2.6.3-3.2_deb9u1_amd64_deb",
    downloaded_file_path = "libfreetype6_2.6.3-3.2+deb9u1_amd64.deb",
    sha256 = "23e7b546543df1ad80a34e9ecdec725e71a5e48b607ef026657aa7687b229791",
    urls = ["http://deb.debian.org/debian/pool/main/f/freetype/libfreetype6_2.6.3-3.2+deb9u1_amd64.deb"],
)

http_file(
    name = "libgail18_2.24.31-2_amd64_deb",
    downloaded_file_path = "libgail18_2.24.31-2_amd64.deb",
    sha256 = "fb042c58738517d4b45fdd1dc56e6236e3e598152831e59f3047e293645861ed",
    urls = ["http://deb.debian.org/debian/pool/main/g/gtk+2.0/libgail18_2.24.31-2_amd64.deb"],
)

http_file(
    name = "libgail-common_2.24.31-2_amd64_deb",
    downloaded_file_path = "libgail-common_2.24.31-2_amd64.deb",
    sha256 = "0cbcf91240034ed1ba9027432e75528334a0ea5b0520b7bb19b149c152f5352e",
    urls = ["http://deb.debian.org/debian/pool/main/g/gtk+2.0/libgail-common_2.24.31-2_amd64.deb"],
)

http_file(
    name = "libgbm1_13.0.6-1_b2_amd64_deb",
    downloaded_file_path = "libgbm1_13.0.6-1+b2_amd64.deb",
    sha256 = "c3dab5305cdb7580e4183e02789b2fb8addbacea7830925e8ee0eb1df0eee599",
    urls = ["http://deb.debian.org/debian/pool/main/m/mesa/libgbm1_13.0.6-1+b2_amd64.deb"],
)

http_file(
    name = "libgdk-pixbuf2.0-0_2.36.5-2_deb9u2_amd64_deb",
    downloaded_file_path = "libgdk-pixbuf2.0-0_2.36.5-2+deb9u2_amd64.deb",
    sha256 = "0dca760e915f5ec6ef2445135d9daf50d9a7246ec9ef6e1386dceab6a2445028",
    urls = ["http://deb.debian.org/debian/pool/main/g/gdk-pixbuf/libgdk-pixbuf2.0-0_2.36.5-2+deb9u2_amd64.deb"],
)

http_file(
    name = "libgdk-pixbuf2.0-common_2.36.5-2_deb9u2_all_deb",
    downloaded_file_path = "libgdk-pixbuf2.0-common_2.36.5-2+deb9u2_all.deb",
    sha256 = "3895bb256529fbb72d9428681af732deee023b3210700857c2febd63022b0921",
    urls = ["http://deb.debian.org/debian/pool/main/g/gdk-pixbuf/libgdk-pixbuf2.0-common_2.36.5-2+deb9u2_all.deb"],
)

http_file(
    name = "libgif7_5.1.4-0.4_amd64_deb",
    downloaded_file_path = "libgif7_5.1.4-0.4_amd64.deb",
    sha256 = "3d7c4e1a578934aa888d73589bf13e292c5c06fb0ff042c15848f07a23adedf5",
    urls = ["http://deb.debian.org/debian/pool/main/g/giflib/libgif7_5.1.4-0.4_amd64.deb"],
)

http_file(
    name = "libgl1-mesa-dri_13.0.6-1_b2_amd64_deb",
    downloaded_file_path = "libgl1-mesa-dri_13.0.6-1+b2_amd64.deb",
    sha256 = "b8ee88fb5b8d823e57d45e088759ba27d4a8a38934e3ad1e0618820573a856c9",
    urls = ["http://deb.debian.org/debian/pool/main/m/mesa/libgl1-mesa-dri_13.0.6-1+b2_amd64.deb"],
)

http_file(
    name = "libgl1-mesa-glx_13.0.6-1_b2_amd64_deb",
    downloaded_file_path = "libgl1-mesa-glx_13.0.6-1+b2_amd64.deb",
    sha256 = "70408e6317beb1066447e2cfb2932b164ef9dffa50cd62395dc14d06d25660eb",
    urls = ["http://deb.debian.org/debian/pool/main/m/mesa/libgl1-mesa-glx_13.0.6-1+b2_amd64.deb"],
)

http_file(
    name = "libglapi-mesa_13.0.6-1_b2_amd64_deb",
    downloaded_file_path = "libglapi-mesa_13.0.6-1+b2_amd64.deb",
    sha256 = "c0b239e277c3d7f96c2106eaab968e6dd40a334fa8e539bf68365d415a175bd7",
    urls = ["http://deb.debian.org/debian/pool/main/m/mesa/libglapi-mesa_13.0.6-1+b2_amd64.deb"],
)

http_file(
    name = "libglib2.0-0_2.50.3-2_deb9u2_amd64_deb",
    downloaded_file_path = "libglib2.0-0_2.50.3-2+deb9u2_amd64.deb",
    sha256 = "a838c4a932f9c30d3fb53f61ea04429497220098b8dec89eb3c835254b7b0fa1",
    urls = ["http://deb.debian.org/debian/pool/main/g/glib2.0/libglib2.0-0_2.50.3-2+deb9u2_amd64.deb"],
)

http_file(
    name = "libglib2.0-data_2.50.3-2_deb9u2_all_deb",
    downloaded_file_path = "libglib2.0-data_2.50.3-2+deb9u2_all.deb",
    sha256 = "b94802554a648eb285e77e2374f7830c0be5e9ee1524198dba770ad5fdd0f5dd",
    urls = ["http://deb.debian.org/debian/pool/main/g/glib2.0/libglib2.0-data_2.50.3-2+deb9u2_all.deb"],
)

http_file(
    name = "libgmp10_6.1.2_dfsg-1_amd64_deb",
    downloaded_file_path = "libgmp10_6.1.2+dfsg-1_amd64.deb",
    sha256 = "4a5ef027aae7d20060899e396113c55906d883d39675d9e9990bcace1acba0d1",
    urls = ["http://deb.debian.org/debian/pool/main/g/gmp/libgmp10_6.1.2+dfsg-1_amd64.deb"],
)

http_file(
    name = "libgnutls30_3.5.8-5_deb9u5_amd64_deb",
    downloaded_file_path = "libgnutls30_3.5.8-5+deb9u5_amd64.deb",
    sha256 = "e43126c249630cc36681ae073746bd8907014a7fa6f56405d631a2083a3fe58e",
    urls = ["http://deb.debian.org/debian/pool/main/g/gnutls28/libgnutls30_3.5.8-5+deb9u5_amd64.deb"],
)

http_file(
    name = "libgpm2_1.20.4-6.2_b1_amd64_deb",
    downloaded_file_path = "libgpm2_1.20.4-6.2+b1_amd64.deb",
    sha256 = "66ef77417645c9951abf3ff5b9e84c16d185e1e98355f3ee33ca75c6d71662e9",
    urls = ["http://deb.debian.org/debian/pool/main/g/gpm/libgpm2_1.20.4-6.2+b1_amd64.deb"],
)

http_file(
    name = "libgraphite2-3_1.3.10-1_amd64_deb",
    downloaded_file_path = "libgraphite2-3_1.3.10-1_amd64.deb",
    sha256 = "abea07610dab52ea704b01231c179ea02fcf6ecb7606e0775fb3150916c8276b",
    urls = ["http://deb.debian.org/debian/pool/main/g/graphite2/libgraphite2-3_1.3.10-1_amd64.deb"],
)

http_file(
    name = "libgssapi-krb5-2_1.15-1_deb9u1_amd64_deb",
    downloaded_file_path = "libgssapi-krb5-2_1.15-1+deb9u1_amd64.deb",
    sha256 = "1be19361962bc3549f310f7da90da7e3b96c5f930e2296d7ea170720455becbb",
    urls = ["http://deb.debian.org/debian/pool/main/k/krb5/libgssapi-krb5-2_1.15-1+deb9u1_amd64.deb"],
)

http_file(
    name = "libgtk2.0-0_2.24.31-2_amd64_deb",
    downloaded_file_path = "libgtk2.0-0_2.24.31-2_amd64.deb",
    sha256 = "2406ad832e6f677de8107d2b2590cf7e4fa03d90bd644810cab76d54c7ced248",
    urls = ["http://deb.debian.org/debian/pool/main/g/gtk+2.0/libgtk2.0-0_2.24.31-2_amd64.deb"],
)

http_file(
    name = "libgtk2.0-bin_2.24.31-2_amd64_deb",
    downloaded_file_path = "libgtk2.0-bin_2.24.31-2_amd64.deb",
    sha256 = "8a69de81cd87eb5a50f3007b7af033d82419a0b90cc9e77fb2ba33e9be37aec6",
    urls = ["http://deb.debian.org/debian/pool/main/g/gtk+2.0/libgtk2.0-bin_2.24.31-2_amd64.deb"],
)

http_file(
    name = "libgtk2.0-common_2.24.31-2_all_deb",
    downloaded_file_path = "libgtk2.0-common_2.24.31-2_all.deb",
    sha256 = "cf9c7c0dd4fc876fe2088c0d23e082e4a8e44c424184bc277577b753f7ca8ced",
    urls = ["http://deb.debian.org/debian/pool/main/g/gtk+2.0/libgtk2.0-common_2.24.31-2_all.deb"],
)

http_file(
    name = "libgtk-3-0_3.22.11-1_amd64_deb",
    downloaded_file_path = "libgtk-3-0_3.22.11-1_amd64.deb",
    sha256 = "cb2b6f725114a23dc16334553851eb71d05b8636ac6618ed3baee3d8fb95d987",
    urls = ["http://deb.debian.org/debian/pool/main/g/gtk+3.0/libgtk-3-0_3.22.11-1_amd64.deb"],
)

http_file(
    name = "libgtk-3-bin_3.22.11-1_amd64_deb",
    downloaded_file_path = "libgtk-3-bin_3.22.11-1_amd64.deb",
    sha256 = "9fe017bf34a262cf36b4a2b2545bfc29409fbfb3d7bdbdb3cbe142238d9c720e",
    urls = ["http://deb.debian.org/debian/pool/main/g/gtk+3.0/libgtk-3-bin_3.22.11-1_amd64.deb"],
)

http_file(
    name = "libgtk-3-common_3.22.11-1_all_deb",
    downloaded_file_path = "libgtk-3-common_3.22.11-1_all.deb",
    sha256 = "8544d0744e11408545a54cdd028f87511995061eed1d411dba45d42028077435",
    urls = ["http://deb.debian.org/debian/pool/main/g/gtk+3.0/libgtk-3-common_3.22.11-1_all.deb"],
)

http_file(
    name = "libharfbuzz0b_1.4.2-1_amd64_deb",
    downloaded_file_path = "libharfbuzz0b_1.4.2-1_amd64.deb",
    sha256 = "7d66151e6f07835f707a073a08e449e1ce971885af71ad6c474e0e85a2439610",
    urls = ["http://deb.debian.org/debian/pool/main/h/harfbuzz/libharfbuzz0b_1.4.2-1_amd64.deb"],
)

http_file(
    name = "libhogweed4_3.3-1_b2_amd64_deb",
    downloaded_file_path = "libhogweed4_3.3-1+b2_amd64.deb",
    sha256 = "71658a201b566540bccefcbd06470cad77db47f5a11ce9754b5df58eb9ce57ff",
    urls = ["http://deb.debian.org/debian/pool/main/n/nettle/libhogweed4_3.3-1+b2_amd64.deb"],
)

http_file(
    name = "libice6_1.0.9-2_amd64_deb",
    downloaded_file_path = "libice6_1.0.9-2_amd64.deb",
    sha256 = "5ab658c7efc05094b69f6d0950486a70df617305fab10983b7d885ab0a750f21",
    urls = ["http://deb.debian.org/debian/pool/main/libi/libice/libice6_1.0.9-2_amd64.deb"],
)

http_file(
    name = "libicu57_57.1-6_deb9u4_amd64_deb",
    downloaded_file_path = "libicu57_57.1-6+deb9u4_amd64.deb",
    sha256 = "11152f642bef2c9ee5386a9a4573fc00bafb62cafe1ec1e925974ac1a58d5296",
    urls = ["http://deb.debian.org/debian/pool/main/i/icu/libicu57_57.1-6+deb9u4_amd64.deb"],
)

http_file(
    name = "libjbig0_2.1-3.1_b2_amd64_deb",
    downloaded_file_path = "libjbig0_2.1-3.1+b2_amd64.deb",
    sha256 = "9646d69eefce505407bf0437ea12fb7c2d47a3fd4434720ba46b642b6dcfd80f",
    urls = ["http://deb.debian.org/debian/pool/main/j/jbigkit/libjbig0_2.1-3.1+b2_amd64.deb"],
)

http_file(
    name = "libjpeg62-turbo_1.5.1-2_deb9u1_amd64_deb",
    downloaded_file_path = "libjpeg62-turbo_1.5.1-2+deb9u1_amd64.deb",
    sha256 = "5693f4dcbcad7dc9a88f49dd41c5bb47661839ea8374030abd867da50cd101a5",
    urls = ["http://security.debian.org/debian-security/pool/updates/main/libj/libjpeg-turbo/libjpeg62-turbo_1.5.1-2+deb9u1_amd64.deb"],
)

http_file(
    name = "libjson-glib-1.0-0_1.2.6-1_amd64_deb",
    downloaded_file_path = "libjson-glib-1.0-0_1.2.6-1_amd64.deb",
    sha256 = "84c98a65540abf9145ed72c4ea6430ffc7f3af44147ef8de773df150c9a3f362",
    urls = ["http://deb.debian.org/debian/pool/main/j/json-glib/libjson-glib-1.0-0_1.2.6-1_amd64.deb"],
)

http_file(
    name = "libjson-glib-1.0-common_1.2.6-1_all_deb",
    downloaded_file_path = "libjson-glib-1.0-common_1.2.6-1_all.deb",
    sha256 = "8aa2a608c5d129f54e0ff72999a02d0a0f68ea9c94a23d2fe34e0ee018cb0c44",
    urls = ["http://deb.debian.org/debian/pool/main/j/json-glib/libjson-glib-1.0-common_1.2.6-1_all.deb"],
)

http_file(
    name = "libk5crypto3_1.15-1_deb9u1_amd64_deb",
    downloaded_file_path = "libk5crypto3_1.15-1+deb9u1_amd64.deb",
    sha256 = "d576e066867e6a62b8664a468443bc90ff9cc17378b1d620726e4cf631e4a34a",
    urls = ["http://deb.debian.org/debian/pool/main/k/krb5/libk5crypto3_1.15-1+deb9u1_amd64.deb"],
)

http_file(
    name = "libkeyutils1_1.5.9-9_amd64_deb",
    downloaded_file_path = "libkeyutils1_1.5.9-9_amd64.deb",
    sha256 = "fbe75e0eb41c9f0f74a2aca3ee6d30bfde7789dede320093c4aca964a435973f",
    urls = ["http://deb.debian.org/debian/pool/main/k/keyutils/libkeyutils1_1.5.9-9_amd64.deb"],
)

http_file(
    name = "libkrb5-3_1.15-1_deb9u1_amd64_deb",
    downloaded_file_path = "libkrb5-3_1.15-1+deb9u1_amd64.deb",
    sha256 = "7b788d4acbf79872756f78704260cf8c2bcfde224c6d927da2a18b5735356e7f",
    urls = ["http://deb.debian.org/debian/pool/main/k/krb5/libkrb5-3_1.15-1+deb9u1_amd64.deb"],
)

http_file(
    name = "libkrb5support0_1.15-1_deb9u1_amd64_deb",
    downloaded_file_path = "libkrb5support0_1.15-1+deb9u1_amd64.deb",
    sha256 = "e0224ec2485a534c8a6ac029e7156df3bfdd4dc9467672a5b6ee5cc1f513c136",
    urls = ["http://deb.debian.org/debian/pool/main/k/krb5/libkrb5support0_1.15-1+deb9u1_amd64.deb"],
)

http_file(
    name = "liblcms2-2_2.8-4_deb9u1_amd64_deb",
    downloaded_file_path = "liblcms2-2_2.8-4+deb9u1_amd64.deb",
    sha256 = "18d45f638c1628790f72a6a4b6502cb3f542feecc0388e15d8f272d8f4c8c03b",
    urls = ["http://deb.debian.org/debian/pool/main/l/lcms2/liblcms2-2_2.8-4+deb9u1_amd64.deb"],
)

http_file(
    name = "libllvm3.9_3.9.1-9_amd64_deb",
    downloaded_file_path = "libllvm3.9_3.9.1-9_amd64.deb",
    sha256 = "c9017a11cb5188f215968a825dd1fdb75e1e12ca601acb25252bfa7d5137b9c5",
    urls = ["http://deb.debian.org/debian/pool/main/l/llvm-toolchain-3.9/libllvm3.9_3.9.1-9_amd64.deb"],
)

http_file(
    name = "libncurses5_6.0_20161126-1_deb9u2_amd64_deb",
    downloaded_file_path = "libncurses5_6.0+20161126-1+deb9u2_amd64.deb",
    sha256 = "68caef5e0d2eb5e199903866fd1631d8f342a80c53373631abbeeee125c0dc3d",
    urls = ["http://deb.debian.org/debian/pool/main/n/ncurses/libncurses5_6.0+20161126-1+deb9u2_amd64.deb"],
)

http_file(
    name = "libnspr4_4.12-6_amd64_deb",
    downloaded_file_path = "libnspr4_4.12-6_amd64.deb",
    sha256 = "6cdd0cf398b5fde85016d1a16533e8cf4823674708d6a69c9b99fd83d01b3792",
    urls = ["http://deb.debian.org/debian/pool/main/n/nspr/libnspr4_4.12-6_amd64.deb"],
)

http_file(
    name = "libnss3_3.26.2-1.1_deb9u1_amd64_deb",
    downloaded_file_path = "libnss3_3.26.2-1.1+deb9u1_amd64.deb",
    sha256 = "e90fbff066d0fac676c0ea102d0f6b083435ebf3fa95d9f53204e12acaebbee0",
    urls = ["http://deb.debian.org/debian/pool/main/n/nss/libnss3_3.26.2-1.1+deb9u1_amd64.deb"],
)

http_file(
    name = "libogg0_1.3.2-1_amd64_deb",
    downloaded_file_path = "libogg0_1.3.2-1_amd64.deb",
    sha256 = "dc596aeecf952e2fba3b1650e50a146a595c8032aec5776c1711bcc4fb075ad0",
    urls = ["http://deb.debian.org/debian/pool/main/libo/libogg/libogg0_1.3.2-1_amd64.deb"],
)

http_file(
    name = "libp11-kit0_0.23.3-2_amd64_deb",
    downloaded_file_path = "libp11-kit0_0.23.3-2_amd64.deb",
    sha256 = "866d778eb205f8eacb6940afb7c763819ce2c0e27146d4b9710de918843e3c25",
    urls = ["http://deb.debian.org/debian/pool/main/p/p11-kit/libp11-kit0_0.23.3-2_amd64.deb"],
)

http_file(
    name = "libpango-1.0-0_1.40.5-1_amd64_deb",
    downloaded_file_path = "libpango-1.0-0_1.40.5-1_amd64.deb",
    sha256 = "2973a15ad26aa1051dce9fa4c0ee7e06e4b03e99cf74b6e8697cb7384b346e8d",
    urls = ["http://deb.debian.org/debian/pool/main/p/pango1.0/libpango-1.0-0_1.40.5-1_amd64.deb"],
)

http_file(
    name = "libpangocairo-1.0-0_1.40.5-1_amd64_deb",
    downloaded_file_path = "libpangocairo-1.0-0_1.40.5-1_amd64.deb",
    sha256 = "c7bb62778c4e6c8086028e50656c3eff6e238c1467da6f3020c3d843668060d9",
    urls = ["http://deb.debian.org/debian/pool/main/p/pango1.0/libpangocairo-1.0-0_1.40.5-1_amd64.deb"],
)

http_file(
    name = "libpangoft2-1.0-0_1.40.5-1_amd64_deb",
    downloaded_file_path = "libpangoft2-1.0-0_1.40.5-1_amd64.deb",
    sha256 = "d668b89229869a68cc411a25feff5016ff76c5ed0ae23855196f2a46f8f88e75",
    urls = ["http://deb.debian.org/debian/pool/main/p/pango1.0/libpangoft2-1.0-0_1.40.5-1_amd64.deb"],
)

http_file(
    name = "libpciaccess0_0.13.4-1_b2_amd64_deb",
    downloaded_file_path = "libpciaccess0_0.13.4-1+b2_amd64.deb",
    sha256 = "d484862d96d547fbe375c5b834e59b986a52750e44760432993fc60e51caf95e",
    urls = ["http://deb.debian.org/debian/pool/main/libp/libpciaccess/libpciaccess0_0.13.4-1+b2_amd64.deb"],
)

http_file(
    name = "libpcsclite1_1.8.20-1_amd64_deb",
    downloaded_file_path = "libpcsclite1_1.8.20-1_amd64.deb",
    sha256 = "c00cb180ab89de498530eb41a4716e5afa040b024cb7f56c08e34e012381d162",
    urls = ["http://deb.debian.org/debian/pool/main/p/pcsc-lite/libpcsclite1_1.8.20-1_amd64.deb"],
)

http_file(
    name = "libpixman-1-0_0.34.0-1_amd64_deb",
    downloaded_file_path = "libpixman-1-0_0.34.0-1_amd64.deb",
    sha256 = "6c4155c4e217481aa728d39d2ba7d6ca6c88bb1e2b342ca24b2714e61903a3e1",
    urls = ["http://deb.debian.org/debian/pool/main/p/pixman/libpixman-1-0_0.34.0-1_amd64.deb"],
)

http_file(
    name = "libpng16-16_1.6.28-1_deb9u1_amd64_deb",
    downloaded_file_path = "libpng16-16_1.6.28-1+deb9u1_amd64.deb",
    sha256 = "1d0b8014cba18f84ce77398da9db9c71e1a8ce53fd8157cd7bf9ccf1d56a42f4",
    urls = ["http://deb.debian.org/debian/pool/main/libp/libpng1.6/libpng16-16_1.6.28-1+deb9u1_amd64.deb"],
)

http_file(
    name = "libproxy1v5_0.4.14-2_deb9u1_amd64_deb",
    downloaded_file_path = "libproxy1v5_0.4.14-2+deb9u1_amd64.deb",
    sha256 = "241043137766840b36bbd37a1b3043834377bf82a88b818a1011f26a709733e2",
    urls = ["http://security.debian.org/debian-security/pool/updates/main/libp/libproxy/libproxy1v5_0.4.14-2+deb9u1_amd64.deb"],
)

http_file(
    name = "libpulse0_10.0-1_deb9u1_amd64_deb",
    downloaded_file_path = "libpulse0_10.0-1+deb9u1_amd64.deb",
    sha256 = "3990435f693a417120c21e31ca38944530300a1f016b771e440c55d9b2c207dd",
    urls = ["http://deb.debian.org/debian/pool/main/p/pulseaudio/libpulse0_10.0-1+deb9u1_amd64.deb"],
)

http_file(
    name = "librest-0.7-0_0.8.0-2_amd64_deb",
    downloaded_file_path = "librest-0.7-0_0.8.0-2_amd64.deb",
    sha256 = "38bf2f1b827c9bb5b2de9eddbfecd72a1c02cca258f75001bc639de5175a471f",
    urls = ["http://deb.debian.org/debian/pool/main/libr/librest/librest-0.7-0_0.8.0-2_amd64.deb"],
)

http_file(
    name = "librsvg2-2_2.40.21-0_deb9u1_amd64_deb",
    downloaded_file_path = "librsvg2-2_2.40.21-0+deb9u1_amd64.deb",
    sha256 = "2fd33233f2da17c2e9aeaa7fb1026077ee60da7574803652b0ee7742c1a333af",
    urls = ["http://security.debian.org/debian-security/pool/updates/main/libr/librsvg/librsvg2-2_2.40.21-0+deb9u1_amd64.deb"],
)

http_file(
    name = "librsvg2-common_2.40.21-0_deb9u1_amd64_deb",
    downloaded_file_path = "librsvg2-common_2.40.21-0+deb9u1_amd64.deb",
    sha256 = "96a7ae726fed02fb540075942320670652805c599949e3293e07362e6b526f4a",
    urls = ["http://security.debian.org/debian-security/pool/updates/main/libr/librsvg/librsvg2-common_2.40.21-0+deb9u1_amd64.deb"],
)

http_file(
    name = "libsensors4_3.4.0-4_amd64_deb",
    downloaded_file_path = "libsensors4_3.4.0-4_amd64.deb",
    sha256 = "69dd894a529c88e1dedb71f4dbe5210f8882a0606a547bca2ac172327a6895d3",
    urls = ["http://deb.debian.org/debian/pool/main/l/lm-sensors/libsensors4_3.4.0-4_amd64.deb"],
)

http_file(
    name = "libsm6_1.2.2-1_b3_amd64_deb",
    downloaded_file_path = "libsm6_1.2.2-1+b3_amd64.deb",
    sha256 = "8a7632374e0d570f985b766ce31df4d644803772e387fe2b3db9838c68e6a75d",
    urls = ["http://deb.debian.org/debian/pool/main/libs/libsm/libsm6_1.2.2-1+b3_amd64.deb"],
)

http_file(
    name = "libsndfile1_1.0.27-3_amd64_deb",
    downloaded_file_path = "libsndfile1_1.0.27-3_amd64.deb",
    sha256 = "03159852c6c34d1c00919537d83c1c76a692a416fb0b316d7cd09fbd119629e6",
    urls = ["http://deb.debian.org/debian/pool/main/libs/libsndfile/libsndfile1_1.0.27-3_amd64.deb"],
)

http_file(
    name = "libsoup2.4-1_2.56.0-2_deb9u2_amd64_deb",
    downloaded_file_path = "libsoup2.4-1_2.56.0-2+deb9u2_amd64.deb",
    sha256 = "0c96375e6dec57b40c1ae2e32b894afc0b55a460da39e55b22ab0fbcdcebfbde",
    urls = ["http://deb.debian.org/debian/pool/main/libs/libsoup2.4/libsoup2.4-1_2.56.0-2+deb9u2_amd64.deb"],
)

http_file(
    name = "libsoup-gnome2.4-1_2.56.0-2_deb9u2_amd64_deb",
    downloaded_file_path = "libsoup-gnome2.4-1_2.56.0-2+deb9u2_amd64.deb",
    sha256 = "f622ab2e5145896c862c5319ddb7811bbaf792ab9a67dd50bc3d3273dca54fc7",
    urls = ["http://deb.debian.org/debian/pool/main/libs/libsoup2.4/libsoup-gnome2.4-1_2.56.0-2+deb9u2_amd64.deb"],
)

http_file(
    name = "libsqlite3-0_3.16.2-5_deb9u2_amd64_deb",
    downloaded_file_path = "libsqlite3-0_3.16.2-5+deb9u2_amd64.deb",
    sha256 = "7df54fe22cbf809edaeb5c1ae152dda98b3a7097f03d1e3864eda4d8e581eccb",
    urls = ["http://security.debian.org/debian-security/pool/updates/main/s/sqlite3/libsqlite3-0_3.16.2-5+deb9u2_amd64.deb"],
)

http_file(
    name = "libssl1.1_1.1.0l-1_deb9u1_amd64_deb",
    downloaded_file_path = "libssl1.1_1.1.0l-1~deb9u1_amd64.deb",
    sha256 = "385ce03f4b995e2f756ff92f8fb2c431f51c51866e08695d329223ca6cd3bfaa",
    urls = ["http://deb.debian.org/debian/pool/main/o/openssl/libssl1.1_1.1.0l-1~deb9u1_amd64.deb"],
)

http_file(
    name = "libtasn1-6_4.10-1.1_deb9u1_amd64_deb",
    downloaded_file_path = "libtasn1-6_4.10-1.1+deb9u1_amd64.deb",
    sha256 = "48514239ecf51afe060445db92b69cee31e00af3d4485af160a23264d9a4119a",
    urls = ["http://deb.debian.org/debian/pool/main/libt/libtasn1-6/libtasn1-6_4.10-1.1+deb9u1_amd64.deb"],
)

http_file(
    name = "libthai0_0.1.26-1_amd64_deb",
    downloaded_file_path = "libthai0_0.1.26-1_amd64.deb",
    sha256 = "e9cfd37dc2b1e067ee70cd17c153235c852b83754cb039e86e554c3376853f3b",
    urls = ["http://deb.debian.org/debian/pool/main/libt/libthai/libthai0_0.1.26-1_amd64.deb"],
)

http_file(
    name = "libthai-data_0.1.26-1_all_deb",
    downloaded_file_path = "libthai-data_0.1.26-1_all.deb",
    sha256 = "9e1709138f7d324fbcb6b62d48f6a2b365630e8f81c42db12e04d03d0e71f9f6",
    urls = ["http://deb.debian.org/debian/pool/main/libt/libthai/libthai-data_0.1.26-1_all.deb"],
)

http_file(
    name = "libtiff5_4.0.8-2_deb9u5_amd64_deb",
    downloaded_file_path = "libtiff5_4.0.8-2+deb9u5_amd64.deb",
    sha256 = "71abb8266d744718db819a476a6f469a242c294a446b36724f3745f2ea673b2e",
    urls = ["http://deb.debian.org/debian/pool/main/t/tiff/libtiff5_4.0.8-2+deb9u5_amd64.deb"],
)

http_file(
    name = "libtxc-dxtn-s2tc_1.0_git20151227-2_amd64_deb",
    downloaded_file_path = "libtxc-dxtn-s2tc_1.0+git20151227-2_amd64.deb",
    sha256 = "0ec9f197595a6dde9744f971dd86c3cca169382066b8bdaf302800213343dc71",
    urls = ["http://deb.debian.org/debian/pool/main/s/s2tc/libtxc-dxtn-s2tc_1.0+git20151227-2_amd64.deb"],
)

http_file(
    name = "libvorbis0a_1.3.5-4_deb9u2_amd64_deb",
    downloaded_file_path = "libvorbis0a_1.3.5-4+deb9u2_amd64.deb",
    sha256 = "abb3ca2ea0b611d7dc6822c9ba6029bebbc31431b35289388cd703938ded5f4f",
    urls = ["http://deb.debian.org/debian/pool/main/libv/libvorbis/libvorbis0a_1.3.5-4+deb9u2_amd64.deb"],
)

http_file(
    name = "libvorbisenc2_1.3.5-4_deb9u2_amd64_deb",
    downloaded_file_path = "libvorbisenc2_1.3.5-4+deb9u2_amd64.deb",
    sha256 = "3a61c24db018c2f3a3c9c07eaea0a09fc3a0ffa2e6ccef1cb37e8f64574b9f9d",
    urls = ["http://deb.debian.org/debian/pool/main/libv/libvorbis/libvorbisenc2_1.3.5-4+deb9u2_amd64.deb"],
)

http_file(
    name = "libwayland-client0_1.12.0-1_deb9u1_amd64_deb",
    downloaded_file_path = "libwayland-client0_1.12.0-1+deb9u1_amd64.deb",
    sha256 = "c1083bb3a1d55801733c8a44496c7c34f866a1276eb8fdd633e71540532bebac",
    urls = ["http://deb.debian.org/debian/pool/main/w/wayland/libwayland-client0_1.12.0-1+deb9u1_amd64.deb"],
)

http_file(
    name = "libwayland-cursor0_1.12.0-1_deb9u1_amd64_deb",
    downloaded_file_path = "libwayland-cursor0_1.12.0-1+deb9u1_amd64.deb",
    sha256 = "5d7818a942a4c99b8c94f216bf7583cebeb17e394abb5d18c7a79b71025dac71",
    urls = ["http://deb.debian.org/debian/pool/main/w/wayland/libwayland-cursor0_1.12.0-1+deb9u1_amd64.deb"],
)

http_file(
    name = "libwayland-egl1-mesa_13.0.6-1_b2_amd64_deb",
    downloaded_file_path = "libwayland-egl1-mesa_13.0.6-1+b2_amd64.deb",
    sha256 = "86d39e2781387d7d797b8525bafd078948deb65ceb5f3d04eabcf9b279cb0217",
    urls = ["http://deb.debian.org/debian/pool/main/m/mesa/libwayland-egl1-mesa_13.0.6-1+b2_amd64.deb"],
)

http_file(
    name = "libwayland-server0_1.12.0-1_deb9u1_amd64_deb",
    downloaded_file_path = "libwayland-server0_1.12.0-1+deb9u1_amd64.deb",
    sha256 = "47160e3351f3601bcf554ad2f7a197bc85622bbcea0cf8213650226eddee44a8",
    urls = ["http://deb.debian.org/debian/pool/main/w/wayland/libwayland-server0_1.12.0-1+deb9u1_amd64.deb"],
)

http_file(
    name = "libwrap0_7.6.q-26_amd64_deb",
    downloaded_file_path = "libwrap0_7.6.q-26_amd64.deb",
    sha256 = "55b60972e3992aa742b511db98b9ef403b50f75917654b34c7c012f012e653a0",
    urls = ["http://deb.debian.org/debian/pool/main/t/tcp-wrappers/libwrap0_7.6.q-26_amd64.deb"],
)

http_file(
    name = "libx11-6_1.6.4-3_deb9u3_amd64_deb",
    downloaded_file_path = "libx11-6_1.6.4-3+deb9u3_amd64.deb",
    sha256 = "c2709a3dc69a20af48333b75a5604bbd6e377b677f787e672abbf3bccb8022e6",
    urls = ["http://security.debian.org/debian-security/pool/updates/main/libx/libx11/libx11-6_1.6.4-3+deb9u3_amd64.deb"],
)

http_file(
    name = "libx11-data_1.6.4-3_deb9u3_all_deb",
    downloaded_file_path = "libx11-data_1.6.4-3+deb9u3_all.deb",
    sha256 = "73bfd1c743f4181a1157e882dc04efede61533e3706e2b776b02078de1596eac",
    urls = ["http://security.debian.org/debian-security/pool/updates/main/libx/libx11/libx11-data_1.6.4-3+deb9u3_all.deb"],
)

http_file(
    name = "libx11-xcb1_1.6.4-3_deb9u3_amd64_deb",
    downloaded_file_path = "libx11-xcb1_1.6.4-3+deb9u3_amd64.deb",
    sha256 = "8103faea4fa8d36d978ac3586c8b8c80f35c6154a6952ea53932809f2f28ee76",
    urls = ["http://security.debian.org/debian-security/pool/updates/main/libx/libx11/libx11-xcb1_1.6.4-3+deb9u3_amd64.deb"],
)

http_file(
    name = "libxau6_1.0.8-1_amd64_deb",
    downloaded_file_path = "libxau6_1.0.8-1_amd64.deb",
    sha256 = "b03b2d0d400c2002a2d38300bd6630306abb0ff325c3d4a4447ecceb58335228",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxau/libxau6_1.0.8-1_amd64.deb"],
)

http_file(
    name = "libxaw7_1.0.13-1_b2_amd64_deb",
    downloaded_file_path = "libxaw7_1.0.13-1+b2_amd64.deb",
    sha256 = "00238151437d6e3458af3b9b8e7a4b35c3d56bad352ef9e345791ea0876f9e2b",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxaw/libxaw7_1.0.13-1+b2_amd64.deb"],
)

http_file(
    name = "libxcb1_1.12-1_amd64_deb",
    downloaded_file_path = "libxcb1_1.12-1_amd64.deb",
    sha256 = "358ac6d450042d1792e3b2093ed73530774e6bd7600536a2acc327b83b201384",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxcb/libxcb1_1.12-1_amd64.deb"],
)

http_file(
    name = "libxcb-dri2-0_1.12-1_amd64_deb",
    downloaded_file_path = "libxcb-dri2-0_1.12-1_amd64.deb",
    sha256 = "a5417613621ba9210b6aa15767cffe84480a4334631875443abff368b9330833",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxcb/libxcb-dri2-0_1.12-1_amd64.deb"],
)

http_file(
    name = "libxcb-dri3-0_1.12-1_amd64_deb",
    downloaded_file_path = "libxcb-dri3-0_1.12-1_amd64.deb",
    sha256 = "f549fd40ad536d40eb1125786f4dfc087506783183cc5c46fa925fd31000c0e5",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxcb/libxcb-dri3-0_1.12-1_amd64.deb"],
)

http_file(
    name = "libxcb-glx0_1.12-1_amd64_deb",
    downloaded_file_path = "libxcb-glx0_1.12-1_amd64.deb",
    sha256 = "bdb1279e76defae1ad1bc9a0ce91c57457296877feaad1ee1a6ec50dbde34dbd",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxcb/libxcb-glx0_1.12-1_amd64.deb"],
)

http_file(
    name = "libxcb-present0_1.12-1_amd64_deb",
    downloaded_file_path = "libxcb-present0_1.12-1_amd64.deb",
    sha256 = "18e4a8439ab7ea178e5df2d52c20024e80965ca106a625e980edb4ccbddc08bd",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxcb/libxcb-present0_1.12-1_amd64.deb"],
)

http_file(
    name = "libxcb-render0_1.12-1_amd64_deb",
    downloaded_file_path = "libxcb-render0_1.12-1_amd64.deb",
    sha256 = "127ebbad060f4ba88c174b980c27cb4458e9782c65349d80034c3feb012c7343",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxcb/libxcb-render0_1.12-1_amd64.deb"],
)

http_file(
    name = "libxcb-shape0_1.12-1_amd64_deb",
    downloaded_file_path = "libxcb-shape0_1.12-1_amd64.deb",
    sha256 = "c0316e53205d5a5502e1f455dcca56c133a5c180b751af3f04c95cc268a94249",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxcb/libxcb-shape0_1.12-1_amd64.deb"],
)

http_file(
    name = "libxcb-shm0_1.12-1_amd64_deb",
    downloaded_file_path = "libxcb-shm0_1.12-1_amd64.deb",
    sha256 = "3bed0565cfd144bc4f1752985572c3d62b4dd193fb1f1c4cb5f05f82878b459b",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxcb/libxcb-shm0_1.12-1_amd64.deb"],
)

http_file(
    name = "libxcb-sync1_1.12-1_amd64_deb",
    downloaded_file_path = "libxcb-sync1_1.12-1_amd64.deb",
    sha256 = "3db9c51ce186f579cdb79146843ea4d9b0e54a9e46a64c552ef5959683f291e6",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxcb/libxcb-sync1_1.12-1_amd64.deb"],
)

http_file(
    name = "libxcb-xfixes0_1.12-1_amd64_deb",
    downloaded_file_path = "libxcb-xfixes0_1.12-1_amd64.deb",
    sha256 = "28b114df8ae2c211e8f03219986c949bc8f86a89d3dd0a2f1651df3baa410696",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxcb/libxcb-xfixes0_1.12-1_amd64.deb"],
)

http_file(
    name = "libxcomposite1_0.4.4-2_amd64_deb",
    downloaded_file_path = "libxcomposite1_0.4.4-2_amd64.deb",
    sha256 = "043c878356954f4521c401b160d554809115c472ca384d9f793c1c7542316eb9",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxcomposite/libxcomposite1_0.4.4-2_amd64.deb"],
)

http_file(
    name = "libxcursor1_1.1.14-1_deb9u2_amd64_deb",
    downloaded_file_path = "libxcursor1_1.1.14-1+deb9u2_amd64.deb",
    sha256 = "af4908f3f2bcfe78586823eaf8ed65d838936cb26698c520538717367d836dc6",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxcursor/libxcursor1_1.1.14-1+deb9u2_amd64.deb"],
)

http_file(
    name = "libxdamage1_1.1.4-2_b3_amd64_deb",
    downloaded_file_path = "libxdamage1_1.1.4-2+b3_amd64.deb",
    sha256 = "860d474e576074711a58e248feb9fb62086f641cbfa986145cc6c105ef750cc5",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxdamage/libxdamage1_1.1.4-2+b3_amd64.deb"],
)

http_file(
    name = "libxdmcp6_1.1.2-3_amd64_deb",
    downloaded_file_path = "libxdmcp6_1.1.2-3_amd64.deb",
    sha256 = "ecb8536f5fb34543b55bb9dc5f5b14c9dbb4150a7bddb3f2287b7cab6e9d25ef",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxdmcp/libxdmcp6_1.1.2-3_amd64.deb"],
)

http_file(
    name = "libxext6_1.3.3-1_b2_amd64_deb",
    downloaded_file_path = "libxext6_1.3.3-1+b2_amd64.deb",
    sha256 = "724901105792e983bd0e7c2b46960cd925dd6a2b33b5ee999b4e80aaf624b082",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxext/libxext6_1.3.3-1+b2_amd64.deb"],
)

http_file(
    name = "libxfixes3_5.0.3-1_amd64_deb",
    downloaded_file_path = "libxfixes3_5.0.3-1_amd64.deb",
    sha256 = "3b307490c669accd52dc627ad4dc269a03632ca512fbc7b185b572f76608ff4e",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxfixes/libxfixes3_5.0.3-1_amd64.deb"],
)

http_file(
    name = "libxft2_2.3.2-1_b2_amd64_deb",
    downloaded_file_path = "libxft2_2.3.2-1+b2_amd64.deb",
    sha256 = "25e6bdcfdccdb332b2d415b98170c1fe4841156397dfb04368ac6a9631401670",
    urls = ["http://deb.debian.org/debian/pool/main/x/xft/libxft2_2.3.2-1+b2_amd64.deb"],
)

http_file(
    name = "libxi6_1.7.9-1_amd64_deb",
    downloaded_file_path = "libxi6_1.7.9-1_amd64.deb",
    sha256 = "fe26733adf2025f184bf904caf088a5d3f6aa29a8863b616af9cafaad85b1237",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxi/libxi6_1.7.9-1_amd64.deb"],
)

http_file(
    name = "libxinerama1_1.1.3-1_b3_amd64_deb",
    downloaded_file_path = "libxinerama1_1.1.3-1+b3_amd64.deb",
    sha256 = "56977ee53b18388cc8735dc7a64e709c08c70104344b4f11f255470f08e58c00",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxinerama/libxinerama1_1.1.3-1+b3_amd64.deb"],
)

http_file(
    name = "libxkbcommon0_0.7.1-2_deb9u1_amd64_deb",
    downloaded_file_path = "libxkbcommon0_0.7.1-2~deb9u1_amd64.deb",
    sha256 = "ce9b0fd427e47e270a57f7b5b09530844cce1fb17a387c08dd5e99715379d7ee",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxkbcommon/libxkbcommon0_0.7.1-2~deb9u1_amd64.deb"],
)

http_file(
    name = "libxml2_2.9.4_dfsg1-2.2_deb9u3_amd64_deb",
    downloaded_file_path = "libxml2_2.9.4+dfsg1-2.2+deb9u3_amd64.deb",
    sha256 = "7727f81f0cdeaa9122fcf715c2e591e818f34d7a75f2fbdefecdfde1a0a8cb7a",
    urls = ["http://security.debian.org/debian-security/pool/updates/main/libx/libxml2/libxml2_2.9.4+dfsg1-2.2+deb9u3_amd64.deb"],
)

http_file(
    name = "libxmu6_1.1.2-2_amd64_deb",
    downloaded_file_path = "libxmu6_1.1.2-2_amd64.deb",
    sha256 = "e49866f3de9642e0bcee3e2a49b0f1f222155b62e839f1bf22fdd51c5248464e",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxmu/libxmu6_1.1.2-2_amd64.deb"],
)

http_file(
    name = "libxmuu1_1.1.2-2_amd64_deb",
    downloaded_file_path = "libxmuu1_1.1.2-2_amd64.deb",
    sha256 = "1b2017da6798680d9efbd1c3aeda9af3ef1f459a367b88fb0640764f2b0d539b",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxmu/libxmuu1_1.1.2-2_amd64.deb"],
)

http_file(
    name = "libxpm4_3.5.12-1_amd64_deb",
    downloaded_file_path = "libxpm4_3.5.12-1_amd64.deb",
    sha256 = "49e64f0923cdecb2aaf6c93f176c25f63b841da2a501651ae23070f998967aa7",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxpm/libxpm4_3.5.12-1_amd64.deb"],
)

http_file(
    name = "libxrandr2_1.5.1-1_amd64_deb",
    downloaded_file_path = "libxrandr2_1.5.1-1_amd64.deb",
    sha256 = "8fdd8ba4a8ad819731d6bbd903b52851a2ec2f9ef4139d880e9be421ea61338c",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxrandr/libxrandr2_1.5.1-1_amd64.deb"],
)

http_file(
    name = "libxrender1_0.9.10-1_amd64_deb",
    downloaded_file_path = "libxrender1_0.9.10-1_amd64.deb",
    sha256 = "3ea17d07b5aa89012130e2acd92f0fc0ea67314e2f5eab6e33930ef688f48294",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxrender/libxrender1_0.9.10-1_amd64.deb"],
)

http_file(
    name = "libxshmfence1_1.2-1_b2_amd64_deb",
    downloaded_file_path = "libxshmfence1_1.2-1+b2_amd64.deb",
    sha256 = "1bad7fcf1c6b2c2dceec2c433332769a45f4d42ce173dcfbabbd1053b776c144",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxshmfence/libxshmfence1_1.2-1+b2_amd64.deb"],
)

http_file(
    name = "libxt6_1.1.5-1_amd64_deb",
    downloaded_file_path = "libxt6_1.1.5-1_amd64.deb",
    sha256 = "e388b0a1b0a0951e9087375ddd7f89d556e7043edc2e82c268a4fa25452b340b",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxt/libxt6_1.1.5-1_amd64.deb"],
)

http_file(
    name = "libxtst6_1.2.3-1_amd64_deb",
    downloaded_file_path = "libxtst6_1.2.3-1_amd64.deb",
    sha256 = "7072f9be17abdb9c5af7d052b19c84d1a6c1c13c30c120a98d284ba73d2da73f",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxtst/libxtst6_1.2.3-1_amd64.deb"],
)

http_file(
    name = "libxv1_1.0.11-1_amd64_deb",
    downloaded_file_path = "libxv1_1.0.11-1_amd64.deb",
    sha256 = "27c1d7435d02c0e9a7d831b290141997c957c78379857b63f6e2a0589456cea5",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxv/libxv1_1.0.11-1_amd64.deb"],
)

http_file(
    name = "libxxf86dga1_1.1.4-1_b3_amd64_deb",
    downloaded_file_path = "libxxf86dga1_1.1.4-1+b3_amd64.deb",
    sha256 = "ffe9751a60da2154a226edd0e03af055d6280ad9f00e18ec78c02ab63df27339",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxxf86dga/libxxf86dga1_1.1.4-1+b3_amd64.deb"],
)

http_file(
    name = "libxxf86vm1_1.1.4-1_b2_amd64_deb",
    downloaded_file_path = "libxxf86vm1_1.1.4-1+b2_amd64.deb",
    sha256 = "6f4ca916aaec26d7000fa7f58de3f71119309ab7590ce1f517abfe1825a676c7",
    urls = ["http://deb.debian.org/debian/pool/main/libx/libxxf86vm/libxxf86vm1_1.1.4-1+b2_amd64.deb"],
)

http_file(
    name = "openjdk-8-jre_8u265-b01-0_deb9u1_amd64_deb",
    downloaded_file_path = "openjdk-8-jre_8u265-b01-0+deb9u1_amd64.deb",
    sha256 = "66dc8c41acfe5af71aaf1bc0b32a5a11da6bbdb29172bf6e360fed61b2335cdc",
    urls = ["http://security.debian.org/debian-security/pool/updates/main/o/openjdk-8/openjdk-8-jre_8u265-b01-0+deb9u1_amd64.deb"],
)

http_file(
    name = "openjdk-8-jre-headless_8u265-b01-0_deb9u1_amd64_deb",
    downloaded_file_path = "openjdk-8-jre-headless_8u265-b01-0+deb9u1_amd64.deb",
    sha256 = "2eb75fde8a8a7b70a777f0fc9c081df4b31ef438902e23cea366c25110ab69cf",
    urls = ["http://security.debian.org/debian-security/pool/updates/main/o/openjdk-8/openjdk-8-jre-headless_8u265-b01-0+deb9u1_amd64.deb"],
)

http_file(
    name = "openssl_1.1.0l-1_deb9u1_amd64_deb",
    downloaded_file_path = "openssl_1.1.0l-1~deb9u1_amd64.deb",
    sha256 = "d9f6a3baca51587eef51a502011d21e1eb56328ebe94db92146de1224306add7",
    urls = ["http://deb.debian.org/debian/pool/main/o/openssl/openssl_1.1.0l-1~deb9u1_amd64.deb"],
)

http_file(
    name = "sgml-base_1.29_all_deb",
    downloaded_file_path = "sgml-base_1.29_all.deb",
    sha256 = "bca9413f03c61702820c8d577d1ca2e059b08f9c00ca0ea2d9e64632533dc6a0",
    urls = ["http://deb.debian.org/debian/pool/main/s/sgml-base/sgml-base_1.29_all.deb"],
)

http_file(
    name = "shared-mime-info_1.8-1_deb9u1_amd64_deb",
    downloaded_file_path = "shared-mime-info_1.8-1+deb9u1_amd64.deb",
    sha256 = "d6591f13ee1200c4f0b5581c2299eb7b8097a6b04742dc333e34a7bb7ba47532",
    urls = ["http://deb.debian.org/debian/pool/main/s/shared-mime-info/shared-mime-info_1.8-1+deb9u1_amd64.deb"],
)

http_file(
    name = "tcpd_7.6.q-26_amd64_deb",
    downloaded_file_path = "tcpd_7.6.q-26_amd64.deb",
    sha256 = "29a7a7d4a212d701fca27be43c00d54a2f9280d5c82205105879ded0b72e4040",
    urls = ["http://deb.debian.org/debian/pool/main/t/tcp-wrappers/tcpd_7.6.q-26_amd64.deb"],
)

http_file(
    name = "ucf_3.0036_all_deb",
    downloaded_file_path = "ucf_3.0036_all.deb",
    sha256 = "796a65e765d6045007175531d512c720f4eb04e7f3326b79b848bc6123947225",
    urls = ["http://deb.debian.org/debian/pool/main/u/ucf/ucf_3.0036_all.deb"],
)

http_file(
    name = "x11-common_7.7_19_all_deb",
    downloaded_file_path = "x11-common_7.7+19_all.deb",
    sha256 = "221b2e71e0e98b8cafa4fbc674b3fbe293db031c51d35570a3c8cdfb02a5a155",
    urls = ["http://deb.debian.org/debian/pool/main/x/xorg/x11-common_7.7+19_all.deb"],
)

http_file(
    name = "x11-utils_7.7_3_b1_amd64_deb",
    downloaded_file_path = "x11-utils_7.7+3+b1_amd64.deb",
    sha256 = "800ff796785910670c28b8ca7a06c58c4b423f622bd7d87e8fecfbabd6961e5d",
    urls = ["http://deb.debian.org/debian/pool/main/x/x11-utils/x11-utils_7.7+3+b1_amd64.deb"],
)

http_file(
    name = "xdg-user-dirs_0.15-2_b1_amd64_deb",
    downloaded_file_path = "xdg-user-dirs_0.15-2+b1_amd64.deb",
    sha256 = "26f93443c906865cb085a74138ef8bc5703bb98eaf3fa788ea36a832a1b26dc8",
    urls = ["http://deb.debian.org/debian/pool/main/x/xdg-user-dirs/xdg-user-dirs_0.15-2+b1_amd64.deb"],
)

http_file(
    name = "xkb-data_2.19-1_deb9u1_all_deb",
    downloaded_file_path = "xkb-data_2.19-1+deb9u1_all.deb",
    sha256 = "42a659506d453158b02eaa331972316ed4e47faf3c7144a30044a904c70929c3",
    urls = ["http://deb.debian.org/debian/pool/main/x/xkeyboard-config/xkb-data_2.19-1+deb9u1_all.deb"],
)

http_file(
    name = "xml-core_0.17_all_deb",
    downloaded_file_path = "xml-core_0.17_all.deb",
    sha256 = "fd3648f73297e4b77cf87b7f55eecb3cb6bff82b17718463ccea6dfa1b43a383",
    urls = ["http://deb.debian.org/debian/pool/main/x/xml-core/xml-core_0.17_all.deb"],
)
