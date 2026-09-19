# Mindustry iOS v160 builder

Builds an unsigned/sideloadable iOS IPA from the upstream `Anuken/Mindustry` `v160` source using GitHub Actions on macOS.

The workflow checks out the exact Mindustry v160 tag and the matching Arc commit, then runs RoboVM's `ios:createIPA` task and uploads the resulting IPA as a workflow artifact.
