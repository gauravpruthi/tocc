## Makefile.am -- Process this file with automake to produce Makefile.in

# Output and source files.
bin_PROGRAMS = tocc tocc-initialize

tocc_SOURCES = common/exceptions/base_exception.cpp common/exceptions/cmd_usage_exceptions.cpp utilities/errno_translator.cpp utilities/cmd_parser.cpp utilities/string_utils.cpp selectors/selector.cpp selectors/id_selector.cpp selectors/import_file_selector.cpp selectors/query_selector.cpp actions/action.cpp actions/print_action.cpp actions/assign_action.cpp actions/unassign_action.cpp actions/tags_statistics_action.cpp actions/remove_action.cpp actions/set_title_action.cpp engine/cmd_manager.cpp main.cpp

tocc_initialize_SOURCES = utilities/errno_translator.cpp initializer.cpp
