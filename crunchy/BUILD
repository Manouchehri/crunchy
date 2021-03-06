# Copyright 2017 The CrunchyCrypt Authors.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#      http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

# CrunchyCrypt - Safe and Simple Cryptography
#
# CrunchyCrypt is an opensource library offering safe and easy-to-use cryptography
# APIs with a built-in key-versioning protocol.

package(default_visibility = ["//visibility:public"])

licenses(["notice"])  # Apache 2.0

exports_files(["LICENSE"])

package_group(
    name = "internal_pkg",
    packages = [
        "//crunchy/...",
    ],
)

cc_library(
    name = "crunchy_crypter",
    hdrs = ["crunchy_crypter.h"],
    deps = [
        "//crunchy/util:status",
        "@com_google_absl//absl/strings",
    ],
)

cc_library(
    name = "crunchy_signer",
    hdrs = ["crunchy_signer.h"],
    deps = [
        "//crunchy/util:status",
        "@com_google_absl//absl/strings",
    ],
)

cc_library(
    name = "crunchy_macer",
    hdrs = ["crunchy_macer.h"],
    deps = [
        "//crunchy/util:status",
        "@com_google_absl//absl/strings",
    ],
)

cc_library(
    name = "crunchy_hybrid_crypter",
    hdrs = ["crunchy_hybrid_crypter.h"],
    deps = [
        "//crunchy/util:status",
        "@com_google_absl//absl/strings",
    ],
)
