project(MasterThesis NONE)
include(UseLATEX.cmake)
set(PDFLATEX COMPILER pdflatex)
 add_latex_document(MasterThesis.tex
                    BIBFILES ThesisBibTeX.bib
#                    [INPUTS <input_tex_files>]
                    IMAGE_DIRS img
#                    [IMAGES] <image_files>
#                    [CONFIGURE] <tex_files>
#                    [DEPENDS] <tex_files>
#                    [MULTIBIB_NEWCITES] <suffix_list>
#                    USE_BIBLATEX
#                    [USE_INDEX]
#                    [INDEX_NAMES <index_names>]
#                    [USE_GLOSSARY] [USE_NOMENCL]
#                    [FORCE_PDF] [FORCE_DVI] [FORCE_HTML]
#                    [TARGET_NAME] <name>
#                    [EXCLUDE_FROM_ALL]
#                    [EXCLUDE_FROM_DEFAULTS]
)
