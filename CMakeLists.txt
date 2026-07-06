# edb-orgel-plugin — distributable product (VST3 / AU / Standalone).
#
# A thin wrapper over dehli-musikk-sampler-engine: this file states ONLY the product
# identity. Everything else (entry point, asset embed, sample-pack install, custom
# standalone, packaging metadata) comes from dmse_add_plugin — see
# dehli-musikk-sampler-engine/cmake/DmsePlugin.cmake.

dmse_add_plugin(EdbOrgel
    PRODUCT_NAME "EDB-Orgel"
    PLUGIN_CODE  Edbo
    VERSION      1.0.0
)
