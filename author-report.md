# Author quality report

This report explains every source or export finding and how to repair it. Machine-readable detail is in [author-report.json](author-report.json).

## Corpus

| Item | Value |
| --- | ---: |
| Source ref | `ae6b04a` |
| CHMs | 2 |
| Topics | 1630 |
| Images | 583 |
| PDFs | 13 |

## Summary

| Severity | Count |
| --- | ---: |
| Fatal errors | 0 |
| Advisories | 276 |
| Total | 276 |

## Duplicate display title (`duplicate_title`)

- **Severity:** advisory
- **Owner:** RoboHelp
- **Count:** 4
- **How to fix in RoboHelp:** Open the listed topics in RoboHelp and give each page a distinct, descriptive title or heading so search results identify the correct page.

| Source or generated path | Problem | Evidence |
| --- | --- | --- |
| `User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/bibliography_field.htm` | duplicate title 'Bibliography field' appears in 2 topics | {"title": "Bibliography field", "topics": &#91;"User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/bibliography_field.htm", "User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/bibliography_field.htm"&#93;} |
| `User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Complex_Forms.htm` | duplicate title 'Complex Forms' appears in 3 topics | {"title": "Complex Forms", "topics": &#91;"User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Complex_Forms.htm", "User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/Complex_Forms.htm", "User_Interface/Menus/Tools/Configure_Dictionary/Complex_Forms.htm"&#93;} |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/bibliography_field.md` | display title 'bibliography field (bibliography field)': chm/FieldWorks_Language_Explorer_Help/User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/bibliography_field.md, chm/FieldWorks_Language_Explorer_Help/User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/bibliography_field.md | &#91;"chm/FieldWorks_Language_Explorer_Help/User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/bibliography_field.md", "chm/FieldWorks_Language_Explorer_Help/User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/bibliography_field.md"&#93; |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Complex_Forms.md` | display title 'complex forms field': chm/FieldWorks_Language_Explorer_Help/User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Complex_Forms.md, chm/FieldWorks_Language_Explorer_Help/User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/Complex_Forms.md | &#91;"chm/FieldWorks_Language_Explorer_Help/User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Complex_Forms.md", "chm/FieldWorks_Language_Explorer_Help/User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/Complex_Forms.md"&#93; |

## Link case mismatch (`source_link_case`)

- **Severity:** advisory
- **Owner:** RoboHelp
- **Count:** 6
- **How to fix in RoboHelp:** RoboHelp resolves links case-insensitively, so this one opens in the CHM but would 404 on a case-sensitive host. The export publishes the corrected case; open the source topic in RoboHelp and retype the hyperlink to match the target topic's real path so the two stay in step.

| Source or generated path | Problem | Evidence |
| --- | --- | --- |
| `User_Interface/Menus/Parser/Default_XAmple_parser_overview.htm` | ../../../using_tools/texts_&amp;amp;_words_tools/Interlinear_Texts/Analyze_Text_overview.htm | &#91;"User_Interface/Menus/Parser/Default_XAmple_parser_overview.htm", "../../../using_tools/texts_&amp;amp;_words_tools/Interlinear_Texts/Analyze_Text_overview.htm"&#93; |
| `User_Interface/Menus/Parser/Default_XAmple_parser_overview.htm` | ../../../using_tools/texts_&amp;amp;_words_tools/Interlinear_Texts/specify_the_word_gloss.htm | &#91;"User_Interface/Menus/Parser/Default_XAmple_parser_overview.htm", "../../../using_tools/texts_&amp;amp;_words_tools/Interlinear_Texts/specify_the_word_gloss.htm"&#93; |
| `User_Interface/Menus/Parser/Parsing_words_overview.htm` | ../../../using_tools/texts_&amp;amp;_words_tools/Interlinear_Texts/Analyze_Text_overview.htm | &#91;"User_Interface/Menus/Parser/Parsing_words_overview.htm", "../../../using_tools/texts_&amp;amp;_words_tools/Interlinear_Texts/Analyze_Text_overview.htm"&#93; |
| `User_Interface/Menus/Parser/Parsing_words_overview.htm` | ../../../using_tools/texts_&amp;amp;_words_tools/Interlinear_Texts/specify_the_word_gloss.htm | &#91;"User_Interface/Menus/Parser/Parsing_words_overview.htm", "../../../using_tools/texts_&amp;amp;_words_tools/Interlinear_Texts/specify_the_word_gloss.htm"&#93; |
| `User_Interface/Menus/Parser/Phonological_Rule_Based_parser_overview.htm` | ../../../using_tools/texts_&amp;amp;_words_tools/Interlinear_Texts/Analyze_Text_overview.htm | &#91;"User_Interface/Menus/Parser/Phonological_Rule_Based_parser_overview.htm", "../../../using_tools/texts_&amp;amp;_words_tools/Interlinear_Texts/Analyze_Text_overview.htm"&#93; |
| `User_Interface/Menus/Parser/Phonological_Rule_Based_parser_overview.htm` | ../../../using_tools/texts_&amp;amp;_words_tools/Interlinear_Texts/specify_the_word_gloss.htm | &#91;"User_Interface/Menus/Parser/Phonological_Rule_Based_parser_overview.htm", "../../../using_tools/texts_&amp;amp;_words_tools/Interlinear_Texts/specify_the_word_gloss.htm"&#93; |

## Missing local link (`source_missing_link`)

- **Severity:** advisory
- **Owner:** RoboHelp
- **Count:** 16
- **How to fix in RoboHelp:** Open the source topic in RoboHelp, find the hyperlink named in Evidence, and retarget or remove it; then rebuild the CHM.

| Source or generated path | Problem | Evidence |
| --- | --- | --- |
| `Basic_Tasks/Show_data/Show_Word_Cat_in_Cat_Edit.htm` | ../../Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/interlinear_views_background_colors.htm | &#91;"Basic_Tasks/Show_data/Show_Word_Cat_in_Cat_Edit.htm", "../../Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/interlinear_views_background_colors.htm"&#93; |
| `User_Interface/Menus/Data/Data_overview.htm` | ../../../Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/interlinear_views_background_colors.htm | &#91;"User_Interface/Menus/Data/Data_overview.htm", "../../../Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/interlinear_views_background_colors.htm"&#93; |
| `User_Interface/Menus/Parser/Default_XAmple_parser_overview.htm` | ../../../using_tools/texts_&amp;_words_tools/Interlinear_Texts/interlinear_views_background_colors.htm | &#91;"User_Interface/Menus/Parser/Default_XAmple_parser_overview.htm", "../../../using_tools/texts_&amp;_words_tools/Interlinear_Texts/interlinear_views_background_colors.htm"&#93; |
| `User_Interface/Menus/Parser/Edit_Parser_Parameters.htm` | Strata_as_a_String_in_the_Hermit_Crab_properties - OBSOLETE.htm | &#91;"User_Interface/Menus/Parser/Edit_Parser_Parameters.htm", "Strata_as_a_String_in_the_Hermit_Crab_properties - OBSOLETE.htm"&#93; |
| `User_Interface/Menus/Parser/Parse_Current_Word.htm` | ../../../Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/interlinear_views_background_colors.htm | &#91;"User_Interface/Menus/Parser/Parse_Current_Word.htm", "../../../Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/interlinear_views_background_colors.htm"&#93; |
| `User_Interface/Menus/Parser/Parsing_words_overview.htm` | ../../../using_tools/texts_&amp;_words_tools/Interlinear_Texts/interlinear_views_background_colors.htm | &#91;"User_Interface/Menus/Parser/Parsing_words_overview.htm", "../../../using_tools/texts_&amp;_words_tools/Interlinear_Texts/interlinear_views_background_colors.htm"&#93; |
| `User_Interface/Menus/Parser/Phonological_Rule_Based_parser_overview.htm` | ../../../using_tools/texts_&amp;_words_tools/Interlinear_Texts/interlinear_views_background_colors.htm | &#91;"User_Interface/Menus/Parser/Phonological_Rule_Based_parser_overview.htm", "../../../using_tools/texts_&amp;_words_tools/Interlinear_Texts/interlinear_views_background_colors.htm"&#93; |
| `User_Interface/Toolbars/Insert_toolbar.htm` | ../../Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/interlinear_views_background_colors.htm | &#91;"User_Interface/Toolbars/Insert_toolbar.htm", "../../Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/interlinear_views_background_colors.htm"&#93; |
| `chm/FieldWorks_Language_Explorer_Help/Basic_Tasks/Show_data/Show_Word_Cat_in_Cat_Edit.md` | target does not exist: ../../Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/interlinear_views_background_colors.md | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Data/Data_overview.md` | target does not exist: ../../../Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/interlinear_views_background_colors.md | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Parser/Default_XAmple_parser_overview.md` | target does not exist: ../../../using_tools/texts_&amp;_words_tools/Interlinear_Texts/interlinear_views_background_colors.md | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Parser/Edit_Parser_Parameters.md` | target does not exist: Strata_as_a_String_in_the_Hermit_Crab_properties%20-%20OBSOLETE.md | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Parser/Parse_Current_Word.md` | target does not exist: ../../../Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/interlinear_views_background_colors.md | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Parser/Parsing_words_overview.md` | target does not exist: ../../../using_tools/texts_&amp;_words_tools/Interlinear_Texts/interlinear_views_background_colors.md | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Parser/Phonological_Rule_Based_parser_overview.md` | target does not exist: ../../../using_tools/texts_&amp;_words_tools/Interlinear_Texts/interlinear_views_background_colors.md | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Toolbars/Insert_toolbar.md` | raw HTML target does not exist: ../../Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/interlinear_views_background_colors.md | — |

## Raw HTML retained (`raw_html`)

- **Severity:** advisory
- **Owner:** PDF source/RoboHelp
- **Count:** 240
- **How to fix in PDF source/RoboHelp:** Inspect the reported RoboHelp topic or PDF content and the tag names in Problem. Simplify unsupported source markup when practical; otherwise confirm the retained HTML is intentional.

| Source or generated path | Problem | Evidence |
| --- | --- | --- |
| `WW-ConceptualIntro/ConceptualIntroFLEx.pdf` | 4 | &#91;"WW-ConceptualIntro/ConceptualIntroFLEx.pdf", 4&#93; |
| `chm/FieldWorks_Language_Explorer_Help/Advanced_Tasks/Custom_CSS_Override_Files/Custom_CSS_Override_example.md` | raw HTML tags: configurationitem | — |
| `chm/FieldWorks_Language_Explorer_Help/Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_vernacular_writing_systems.md` | raw HTML tags: language&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/Add_a_new_writing_system.md` | raw HTML tags: language&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Advanced_Tasks/Writing_Systems/Encoding_Converters/Encoding_Converters_overview.md` | raw HTML tags: a, language&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Advanced_Tasks/Writing_Systems/Encoding_Converters/Select_the_conversion_type.md` | raw HTML tags: br, p, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/Advanced_Tasks/Writing_Systems/Encoding_Converters/Select_the_converter_mapping.md` | raw HTML tags: sup | — |
| `chm/FieldWorks_Language_Explorer_Help/Advanced_Tasks/Writing_Systems/Encoding_Converters/Select_the_converter_type.md` | raw HTML tags: sup | — |
| `chm/FieldWorks_Language_Explorer_Help/Advanced_Tasks/Writing_Systems/Encoding_Converters/System_language_for_non-Unicode_programs.md` | raw HTML tags: sup | — |
| `chm/FieldWorks_Language_Explorer_Help/Advanced_Tasks/Writing_Systems/Keyboards/Add_an_input_language_Windows.md` | raw HTML tags: a, sup | — |
| `chm/FieldWorks_Language_Explorer_Help/Advanced_Tasks/Writing_Systems/Keyboards/Input_language_for_Keyman_keyboard.md` | raw HTML tags: a, sup | — |
| `chm/FieldWorks_Language_Explorer_Help/Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Collation_in_FieldWorks.md` | raw HTML tags: a, code, k&#96;, p, t''&#96;, tbody, td, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Delete_a_writing_system.md` | raw HTML tags: writing | — |
| `chm/FieldWorks_Language_Explorer_Help/Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Keyboard_tab_Windows.md` | raw HTML tags: sup | — |
| `chm/FieldWorks_Language_Explorer_Help/Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Writing_System_Properties_Converters_tab.md` | raw HTML tags: a, language&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Writing_System_Properties_Fonts_tab.md` | raw HTML tags: a, missing:** | — |
| `chm/FieldWorks_Language_Explorer_Help/Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Writing_System_Properties_General_tab.md` | raw HTML tags: a, language&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Writing_System_Properties_Keyboard_tab.md` | raw HTML tags: a, sup | — |
| `chm/FieldWorks_Language_Explorer_Help/Basic_Tasks/Audio_files/Audio_files_overview.md` | raw HTML tags: headword&#92;, number&#92;, sup | — |
| `chm/FieldWorks_Language_Explorer_Help/Basic_Tasks/Filtering_data/Examples_of_Regular_Expressions.md` | raw HTML tags: a, br, code, em, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/Basic_Tasks/Filtering_data/Regular_Expression_Metacharacters_table.md` | raw HTML tags: a, br, code, em, p, strong, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/Basic_Tasks/Filtering_data/examples_of_combinations_of_regular_expressions.md` | raw HTML tags: a, code, em, p, strong, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/Basic_Tasks/Show_data/Show_data_overview.md` | raw HTML tags: a, br, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/Basic_Tasks/Show_data/Show_in_from_Notebook.md` | raw HTML tags: name&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Basic_Tasks/Show_data/Show_in_from_Word_Analyses.md` | raw HTML tags: item&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Basic_Tasks/Showing_Writing_Systems/Show_WSs_overview.md` | raw HTML tags: name&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Basic_Tasks/Showing_Writing_Systems/configure_field_WSs.md` | raw HTML tags: name&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Basic_Tasks/Spell_Checking/Copy_spelling_dictionary_files.md` | raw HTML tags: sup | — |
| `chm/FieldWorks_Language_Explorer_Help/Basic_Tasks/Spell_Checking/Create_multiple_vern_spell_dicts.md` | raw HTML tags: sup | — |
| `chm/FieldWorks_Language_Explorer_Help/Basic_Tasks/Spell_Checking/Vernacular_spelling_dictionary_files.md` | raw HTML tags: a, sup | — |
| `chm/FieldWorks_Language_Explorer_Help/Basic_Tasks/Spell_Checking/vernacular_spell_checking.md` | raw HTML tags: a, name | — |
| `chm/FieldWorks_Language_Explorer_Help/Beginning_Tasks/Importing_Data/About_encoding_converters.md` | raw HTML tags: a, sup | — |
| `chm/FieldWorks_Language_Explorer_Help/Beginning_Tasks/Importing_Data/Examine_import_preview_results_errors.md` | raw HTML tags: name | — |
| `chm/FieldWorks_Language_Explorer_Help/Beginning_Tasks/Importing_Data/Import_Interlinear_SFM/Step_1_of_3_Import_Files.md` | raw HTML tags: name&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Beginning_Tasks/Importing_Data/Import_Interlinear_SFM/Step_3_of_3_Ready_to_Import.md` | raw HTML tags: name&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Beginning_Tasks/Importing_Data/Import_Notebook_Data/Step_3_of_7_Encoding_conversion.md` | raw HTML tags: already | — |
| `chm/FieldWorks_Language_Explorer_Help/Beginning_Tasks/Importing_Data/Import_SFM_data_examples.md` | raw HTML tags: code, p, strong, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/Beginning_Tasks/Importing_Data/Import_SFM_words_and_glosses/Import_Standard_Format_words_and_glosses.md` | raw HTML tags: name&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Beginning_Tasks/Importing_Data/Import_SFM_words_and_glosses/Step_1_of_3_Import_Files_words_and_glosses.md` | raw HTML tags: name&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Beginning_Tasks/Importing_Data/Import_SFM_words_and_glosses/Step_3_of_3_Ready_to_Import_words_and_glosses.md` | raw HTML tags: name&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Beginning_Tasks/Importing_Data/Specify_language_mapping_dialog_box.md` | raw HTML tags: already | — |
| `chm/FieldWorks_Language_Explorer_Help/Beginning_Tasks/Importing_Data/Step_7_of_8_Readiness.md` | raw HTML tags: your | — |
| `chm/FieldWorks_Language_Explorer_Help/Beginning_Tasks/Importing_Data/Step_8_of_8_Ready_to_Import.md` | raw HTML tags: file | — |
| `chm/FieldWorks_Language_Explorer_Help/Beginning_Tasks/Importing_Data/import_character_mapping_dlg_box.md` | raw HTML tags: no | — |
| `chm/FieldWorks_Language_Explorer_Help/Lexicography_Tasks/Dictionary_and_Lexicon_overview.md` | raw HTML tags: a, br, em, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/Morphology_and_Parsing_Tasks/Morphology_Parsing_Tasks_overview.md` | raw HTML tags: a, em, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/Overview/Migrate_FieldWorks_6.0.4_(or_earlier)_Projects.md` | raw HTML tags: sup | — |
| `chm/FieldWorks_Language_Explorer_Help/Overview/Technical_support.md` | raw HTML tags: a, flexerrors@sil.org | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Field_Descriptions/Field_Types/down_arrow_with_list_example_graphic.md` | raw HTML tags: not | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Field_Descriptions/Grammar/Category_Edit_fields/category_edit_fields_overview.md` | raw HTML tags: a, li, ol, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Field_Descriptions/Grammar/Compound_Rules_fields/Category_field_Compound_Rules.md` | raw HTML tags: not | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Field_Descriptions/Grammar/Environments_fields/String_Representation_field_Environments.md` | raw HTML tags: component&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/Alt_Forms_lev_flds_ov.md` | raw HTML tags: a, li, p, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/Environments_fld_allomorph.md` | raw HTML tags: component&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Entry_level_fields_overview.md` | raw HTML tags: a, li, p, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Environments_field.md` | raw HTML tags: component&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Note_field.md` | raw HTML tags: name&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Grammatical_Info_Details_fields/Category_Info_field.md` | raw HTML tags: not | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Publication_Settings_flds/Referenced_Complex_Forms_Publication_Settings.md` | raw HTML tags: a, em, img, li, p, strong, table, tbody, td, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/Grammatical_Info_field.md` | raw HTML tags: any&#92;, not | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Field_Descriptions/Lists/Custom_Lists_fields_overview.md` | raw HTML tags: em, p, strong, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Field_Descriptions/Lists/Publications/What_is_a_Publication.md` | raw HTML tags: item&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Field_Descriptions/Notebook/Date_Created_field_Ntbk.md` | raw HTML tags: sup | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Field_Descriptions/Notebook/Date_Modified_field_Ntbk.md` | raw HTML tags: sup | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Field_Descriptions/Notebook/Date_of_Event_field_Ntbk.md` | raw HTML tags: sup | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Field_Descriptions/Texts_&amp;_Words/Texts_&amp;_Words_fields_overview.md` | raw HTML tags: a, em, li, ol, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Field_Descriptions/Texts_&amp;_Words/spelling_status_field.md` | raw HTML tags: name&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Edit/Delete.md` | raw HTML tags: item&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Edit/Edit_overview.md` | raw HTML tags: item&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/File/Archive_with_RAMP.md` | raw HTML tags: a, ramp@sil.org, reap@sil.org | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/File/Backup_and_Restore/Back_up_projects_automatically.md` | raw HTML tags: sup | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/File/Backup_and_Restore/Back_up_this_Project.md` | raw HTML tags: sup | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/File/Backup_and_Restore/Backup_folder.md` | raw HTML tags: sup | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/File/Backup_and_Restore/Folder_Structure.md` | raw HTML tags: a, br, em, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/File/Create_Shortcut_on_Desktop.md` | raw HTML tags: a, sup | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/File/Export/Export_Interlinear.md` | raw HTML tags: extension&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/File/Export/Export_Semantic_Domain_Worksheets.md` | raw HTML tags: a, sup | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/File/Export/Export_a_configured_dictionary.md` | raw HTML tags: a, format&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/File/Export/Export_overview.md` | raw HTML tags: a, br, code, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/File/Open_project_in_another_location.md` | raw HTML tags: project | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/File/Print_content.md` | raw HTML tags: a, em, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/File/RAMP_Metadata.md` | raw HTML tags: a, em, li, p, strong, table, tbody, td, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/File/Upload_to_Webonary.md` | raw HTML tags: a, item&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Format/Format_overview.md` | raw HTML tags: a, p, strong, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Format/Styles/Select_the_parent_style.md` | raw HTML tags: default, sup | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Format/Styles/Styles_Font_tab.md` | raw HTML tags: default | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Insert/Insert_overview.md` | raw HTML tags: a, code, em, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Parser/About_parser_parameters.md` | raw HTML tags: a, blockquote, code, em, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Parser/Parser_menu_overview.md` | raw HTML tags: a, br, em, img, li, ol, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Parser/Try_a_word.md` | raw HTML tags: word&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Parser/Try_the_next_pass_example.md` | raw HTML tags: p, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Send_Receive/Get_a_lexicon.md` | raw HTML tags: name&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Send_Receive/Get_a_project.md` | raw HTML tags: name&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Send_Receive/Send_Receive_menu.md` | raw HTML tags: a, code, em, flex_devteam@sil.org, img, li, p, strong, sup, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Classified_Dictionary/Abbreviations_Names_ClassifiedDict.md` | raw HTML tags: a, img, p, strong, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Classified_Dictionary/Manage_Classified_Dictionary_Views.md` | raw HTML tags: name&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/About_the_left_pane.md` | raw HTML tags: a, em, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Citation_Form.md` | raw HTML tags: a, em, img, p, strong, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Complex_Forms.md` | raw HTML tags: a, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Component_References.md` | raw HTML tags: a, br, em, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Components.md` | raw HTML tags: a, br, em, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Cross_References.md` | raw HTML tags: a, em, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Definition.md` | raw HTML tags: a, img, p, strong, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Definition_or_Gloss.md` | raw HTML tags: a, em, img, p, strong, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Dialect_Labels.md` | raw HTML tags: a, img, p, strong, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Etymology.md` | raw HTML tags: a, br, em, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Examples.md` | raw HTML tags: a, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Extended_Note.md` | raw HTML tags: a, br, em, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Grammatical_Info.md` | raw HTML tags: a, code, em, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Headword.md` | raw HTML tags: a, br, em, img, p, strong, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Lexeme_Form.md` | raw HTML tags: a, em, img, p, strong, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Lexical_Relations.md` | raw HTML tags: a, em, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Literal_Meaning.md` | raw HTML tags: a, em, img, p, strong, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Main_Minor_entry.md` | raw HTML tags: a, em, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Manage_Dictionary_Views.md` | raw HTML tags: name&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Minor_Subentries_(Hybrid_view).md` | raw HTML tags: a, em, img, p, strong, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Other_Referenced_Complex_Forms.md` | raw HTML tags: a, br, em, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Pictures.md` | raw HTML tags: a, blockquote, em, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Pronunciations.md` | raw HTML tags: a, em, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Referenced_Complex_Forms.md` | raw HTML tags: a, blockquote, br, em, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/References_Section_(Config._Dict.).md` | raw HTML tags: a, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Secondary_Homograph_number.md` | raw HTML tags: a, em, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Senses_Subsenses.md` | raw HTML tags: a, br, em, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Subentries.md` | raw HTML tags: a, em, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Using_the_Configure_Dictionary_dialog_box.md` | raw HTML tags: item&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Variant_Forms.md` | raw HTML tags: a, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Variant_Forms_(Inflectional_Variants).md` | raw HTML tags: a, br, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Variant_of.md` | raw HTML tags: a, blockquote, em, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/Variants_of_Sense.md` | raw HTML tags: a, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/abbreviation_and_name.md` | raw HTML tags: a, br, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/alternate_forms.md` | raw HTML tags: a, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Dictionary/gloss.md` | raw HTML tags: a, em, img, p, strong, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Document/Classifications.md` | raw HTML tags: a, em, h3, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Document/Configuring_Document_view_styles.md` | raw HTML tags: br, em, field, p, strong, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Document/Configuring_a_Document_view.md` | raw HTML tags: name&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Document/Time_of_Event.md` | raw HTML tags: a, em, h3, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Reversal_Index/Manage_Views_Reversal_Index.md` | raw HTML tags: name&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Reversal_Index/Referenced_Complex_FormsRI.md` | raw HTML tags: a, em, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Reversal_Index/Referenced_Headword,_Primary_Entry_References.md` | raw HTML tags: a, em, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Reversal_Index/Referenced_Headword_Referenced_Senses.md` | raw HTML tags: a, br, em, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Reversal_Index/Referenced_Senses.md` | raw HTML tags: img, p, strong, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Reversal_Index/Reversal_Category.md` | raw HTML tags: a, em, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Reversal_Index/Reversal_Form.md` | raw HTML tags: a, em, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Configure_Reversal_Index/Reversal_Subentries.md` | raw HTML tags: a, br, em, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/Tools/Tools_overview.md` | raw HTML tags: a, em, p, strong, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/View/Scroll_through_your_work.md` | raw HTML tags: br, img, p, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Menus/View/View_overview.md` | raw HTML tags: a, code, em, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Shortcuts/Shortcut_keys_to_move_the_insertion_point.md` | raw HTML tags: a, br, code, em, p, strong, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Shortcuts/shortcut_keys_Lexicon_tools.md` | raw HTML tags: a, br, code, em, img, p, strong, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Shortcuts/shortcut_keys_Lists_tools.md` | raw HTML tags: a, br, code, em, img, p, strong, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Shortcuts/shortcut_keys_Texts_Words_tools.md` | raw HTML tags: a, code, em, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Shortcuts/shortcut_keys_for_use_with_dialog_boxes.md` | raw HTML tags: any&#92;, not | — |
| `chm/FieldWorks_Language_Explorer_Help/User_Interface/Toolbars/Insert_toolbar.md` | raw HTML tags: a, code, em, img, p, strong, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Grammar_tools/Ad_hoc_Rules/delete_an_ad_hoc_rule.md` | raw HTML tags: rule&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Grammar_tools/Category_Edit/Category_Edit_overview.md` | raw HTML tags: a, li, p, table, tbody, td, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Grammar_tools/Category_Edit/Change_the_optionality_of_a_slot.md` | raw HTML tags: name&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Grammar_tools/Category_Edit/Edit_an_Affix_Template_Table.md` | raw HTML tags: affix&#92;, category&#92;, name, name&#92;, slot | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Grammar_tools/Category_Edit/choose_a_default_inflection_class.md` | raw HTML tags: empty&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Grammar_tools/Compound_Rules/Delete_a_Compound_Rule.md` | raw HTML tags: rule&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Grammar_tools/Natural_Classes/Choose_phonological_features(NC).md` | raw HTML tags: n | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Grammar_tools/Natural_Classes/Remove_a_phonological_feature(NC).md` | raw HTML tags: n | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Grammar_tools/Phonemes/Choose_phonological_features.md` | raw HTML tags: n | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Grammar_tools/Phonemes/Remove_a_phonological_feature.md` | raw HTML tags: n | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Grammar_tools/Phonological_Rules/Set_occurrence.md` | raw HTML tags: infinite&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Grammar_tools/Phonological_Rules/Set_phonological_features.md` | raw HTML tags: n | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_Edit_Entries_overview.md` | raw HTML tags: a, p, strong, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_change_inflect_features.md` | raw HTML tags: not | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_change_publications.md` | raw HTML tags: item&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_choose_for_cust_fld.md` | raw HTML tags: field | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_copy_and_mark_forms.md` | raw HTML tags: code, em, p, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lexicon_tools/Dictionary/Select_a_publication.md` | raw HTML tags: item&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lexicon_tools/Lexicon_Edit/Add_Reference_to_Lexical_Relation.md` | raw HTML tags: name****&#92;, name&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_Publish_In_publications.md` | raw HTML tags: item&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_Show_as_Headwords_In.md` | raw HTML tags: item&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_Stem_Allomorph_Label.md` | raw HTML tags: empty&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_a_sense_status.md` | raw HTML tags: empty | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_an_inflection_class.md` | raw HTML tags: name&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_item_Cust_list_field.md` | raw HTML tags: name&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lexicon_tools/Lexicon_Edit/Enter_note_content_in_a_sense.md` | raw HTML tags: name&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lexicon_tools/Lexicon_Edit/Format_a_table.md` | raw HTML tags: a, br, h3, img, li, p, strong, table, tbody, td, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lexicon_tools/Lexicon_Edit/Insert_a_CR_lexical_relation.md` | raw HTML tags: name&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lexicon_tools/Lexicon_Edit/Insert_a_lexical_relation.md` | raw HTML tags: name&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lexicon_tools/Lexicon_Edit/Specify_publishable_lexical_data.md` | raw HTML tags: a, em, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lexicon_tools/Lexicon_Edit/Use_the_Picture_Properties_dialog_box.md` | raw HTML tags: a, https: | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lexicon_tools/Lexicon_Edit/Using_Create_New_Grammatical_Info_dialog_box.md` | raw HTML tags: any&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lexicon_tools/Lexicon_Edit/Using_Edit_Gram_Infodlg.md` | raw HTML tags: any&#92;, not | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lexicon_tools/Lexicon_Edit/change_the_grammatical_info.md` | raw HTML tags: a, br, img, p, strong, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lexicon_tools/Lexicon_Edit/choose_a_sense_type.md` | raw HTML tags: empty&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lexicon_tools/Lexicon_Edit/choose_slots.md` | raw HTML tags: category&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md` | raw HTML tags: a, em, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lexicon_tools/Lexicon_Edit/play_sound_or_movie.md` | raw HTML tags: sup | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lexicon_tools/Reversal_Indexes/change_the_category_of_a_reversal_entry.md` | raw HTML tags: not | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lists_tools/About_Entry_Types.md` | raw HTML tags: a, em, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lists_tools/About_Lexical_Relations.md` | raw HTML tags: a, br, em, img, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lists_tools/Create_new_publication.md` | raw HTML tags: item&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lists_tools/Delete_a_list_item.md` | raw HTML tags: list, list* | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lists_tools/List_item_usage_table.md` | raw HTML tags: a, br, em, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lists_tools/Set_Type_example_entry_collection.md` | raw HTML tags: em, h3, p, strong, table, tbody, td, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lists_tools/Set_Type_example_entry_or_sense_tree.md` | raw HTML tags: em, h3, p, strong, table, tbody, td, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lists_tools/Set_Type_example_entry_sequence_scale.md` | raw HTML tags: em, h3, p, strong, table, tbody, td, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lists_tools/Set_Type_example_entry_tree.md` | raw HTML tags: em, h3, p, strong, table, tbody, td, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lists_tools/Set_Type_example_sense_collection.md` | raw HTML tags: em, h3, p, strong, table, tbody, td, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lists_tools/Set_Type_example_sense_tree.md` | raw HTML tags: em, h3, p, strong, table, tbody, td, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lists_tools/Text_Chart/default_chart_columns.md` | raw HTML tags: a, em, img, li, p, strong, table, tbody, td, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lists_tools/Text_Chart/specify_columns_for_chart.md` | raw HTML tags: a, br, em, img, p, strong, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lists_tools/choose_item_for_list_field.md` | raw HTML tags: name&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Lists_tools/set_type_example_sense_pair.md` | raw HTML tags: em, h3, p, strong, table, tbody, td, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Notebook_tools/Record_Edit_overview/Choose_confidence.md` | raw HTML tags: empty&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Notebook_tools/Record_Edit_overview/Choose_status.md` | raw HTML tags: empty&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Texts_&amp;_Words_tools/Bulk_Edit_Wordforms/Bulk_delete_form_wordform.md` | raw HTML tags: writing | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Texts_&amp;_Words_tools/Complex_Concordance/Complex_Concordance_examples.md` | raw HTML tags: h3, img, p, table, tbody, td, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Texts_&amp;_Words_tools/Complex_Concordance/Select_Tag.md` | raw HTML tags: any&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Texts_&amp;_Words_tools/Complex_Concordance/Set_Occurrence_(Complex_Concordance).md` | raw HTML tags: infinite&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Texts_&amp;_Words_tools/Concordance/Concordance_overview.md` | raw HTML tags: item&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Texts_&amp;_Words_tools/Interlinear_Texts/Configure_Interlinear_lines_right_click.md` | raw HTML tags: current | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Texts_&amp;_Words_tools/Interlinear_Texts/Display_text_in_an_interlinear_view.md` | raw HTML tags: item&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Texts_&amp;_Words_tools/Interlinear_Texts/Morpheme_Break_examples.md` | raw HTML tags: a, em, img, p, table, tbody, td, th, tr | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Texts_&amp;_Words_tools/Interlinear_Texts/Select_the_lexical_sense_for_a_morpheme.md` | raw HTML tags: morpheme&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Texts_&amp;_Words_tools/Interlinear_Texts/add_a_new_sense.md` | raw HTML tags: morpheme&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Texts_&amp;_Words_tools/Interlinear_Texts/interlinear_views_colors.md` | raw HTML tags: a, em, img, li, ol, p, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Texts_&amp;_Words_tools/Interlinear_Texts/specify_a_word_category.md` | raw HTML tags: not | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Texts_&amp;_Words_tools/Interlinear_Texts/specify_the_word_gloss.md` | raw HTML tags: empty&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Texts_&amp;_Words_tools/Interlinear_Texts/texts_edit_overview.md` | raw HTML tags: a, em, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Texts_&amp;_Words_tools/Word_Analyses/Specify_spelling_status.md` | raw HTML tags: item&#92; | — |
| `chm/FieldWorks_Language_Explorer_Help/Using_Tools/Texts_&amp;_Words_tools/Word_list_columns.md` | raw HTML tags: a, em, li, p, strong, table, tbody, td, th, tr, ul | — |
| `chm/Using_Help/Using_Help/Searching_for_Help_Topics/Search_for_words_or_phrases.md` | raw HTML tags: br, code, em, p, table, tbody, td, th, thead, tr | — |
| `chm/Using_Help/Using_Help/Searching_for_Help_Topics/Search_using_boolean_operators.md` | raw HTML tags: br, code, p, table, tbody, td, th, thead, tr | — |
| `chm/Using_Help/Using_Help/Shortcuts/Shortcuts_for_the_Help_window.md` | raw HTML tags: a, code, p, table, tbody, td, th, thead, tr | — |
| `pdf/FieldWorks_Writing_Systems.md` | raw HTML tags: sup | — |
| `pdf/Language_Explorer/Training/Publishing_FLEx_Dictionaries_Using_Microsoft_Word.md` | raw HTML tags: mark, sup | — |
| `pdf/Language_Explorer/Training/Technical_Notes_on_FieldWorks_Send-Receive.md` | raw HTML tags: abbreviation, auni, computerloginname, filename, name, ownseq, sup, u | — |
| `pdf/Language_Explorer/Training/Technical_Notes_on_LinguaLinks_Database_Import.md` | raw HTML tags: annotations6001, entries5005, lexicaldatabase6001, partsofspeech6001, sup, texts6001, u, wordforminventory6001 | — |
| `pdf/Language_Explorer/Training/Technical_Notes_on_SFM_Database_Import.md` | raw HTML tags: already, de, dt, entry, example, ge, hm, lc, lx, ps, re, sd, semanticdomain, sense, sup, va, variant, xe, xv | — |
| `pdf/Language_Explorer/Training/Technical_Notes_on_Writing_Systems.md` | raw HTML tags: language, sup | — |
| `pdf/Language_Explorer/Utilities/AlloGenUserDocumentation.md` | raw HTML tags: sup, u | — |
| `pdf/Language_Explorer/Utilities/PcPatrFLExUserDocumentation.md` | raw HTML tags: br, sup, u | — |
| `pdf/Language_Explorer/Utilities/ToneParsFLExUserDocumentation.md` | raw HTML tags: sup, u | — |
| `pdf/Language_Explorer/Utilities/VarGenUserDocumentation.md` | raw HTML tags: sup, u | — |
| `pdf/Language_Explorer/Utilities/silewp2007_002.md` | raw HTML tags: domain_location, marker, sup, type, value | — |
| `pdf/WW-ConceptualIntro/ConceptualIntroFLEx.md` | raw HTML tags: sup, table, td, th, tr, u | — |

## Replacement character (`source_replacement_character`)

- **Severity:** advisory
- **Owner:** PDF source
- **Count:** 2
- **How to fix in PDF source:** Open the reported source topic or PDF at the page in Evidence and replace the invalid or unsupported source character.

| Source or generated path | Problem | Evidence |
| --- | --- | --- |
| `Language Explorer/Utilities/silewp2007_002.pdf` | source PDF replacement characters: &#91;{'page': 22, 'count': 1, 'codepoints': &#91;'U+001F'&#93;}&#93; | {"source_pdf": "Language Explorer/Utilities/silewp2007_002.pdf", "generated_markdown": "pdf/Language_Explorer/Utilities/silewp2007_002.md", "pages": &#91;{"page": 22, "count": 1, "codepoints": &#91;"U+001F"&#93;}&#93;} |
| `pdf/Language_Explorer/Utilities/silewp2007_002.md` | contains U+FFFD | — |

## Source unsafe URI (`source_unsafe_uri`)

- **Severity:** advisory
- **Owner:** RoboHelp
- **Count:** 4
- **How to fix in RoboHelp:** Open the source topic in RoboHelp, find the URI in Evidence, and replace malformed, file:, or script-like targets with a valid safe link or remove them.

| Source or generated path | Problem | Evidence |
| --- | --- | --- |
| `Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/Select_Language_overview.htm` | httsp://www.ethnologue.com/world | &#91;"Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/Select_Language_overview.htm", "httsp://www.ethnologue.com/world"&#93; |
| `Using_Tools/Lexicon_tools/Lexicon_Edit/Specify_publishable_lexical_data.htm` | file://D:/FieldWorks_Language_Explorer_Help_Dictionary/User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Publication_Settings_flds/Subentries_(Publication_Settings).htm | &#91;"Using_Tools/Lexicon_tools/Lexicon_Edit/Specify_publishable_lexical_data.htm", "file://D:/FieldWorks_Language_Explorer_Help_Dictionary/User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Publication_Settings_flds/Subentries_(Publication_Settings).htm"&#93; |
| `Using_Tools/Lexicon_tools/Lexicon_Edit/Specify_publishable_lexical_data.htm` | file://D:/FieldWorks_Language_Explorer_Help_Dictionary/User_Interface/Menus/Tools/Configure_Dictionary/Main_Minor_entry.htm | &#91;"Using_Tools/Lexicon_tools/Lexicon_Edit/Specify_publishable_lexical_data.htm", "file://D:/FieldWorks_Language_Explorer_Help_Dictionary/User_Interface/Menus/Tools/Configure_Dictionary/Main_Minor_entry.htm"&#93; |
| `Using_Tools/Lexicon_tools/Lexicon_Edit/Specify_publishable_lexical_data.htm` | file://D:/FieldWorks_Language_Explorer_Help_Dictionary/User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Publication_Settings_flds/Show_Minor_Entry_Pub_Set_level.htm | &#91;"Using_Tools/Lexicon_tools/Lexicon_Edit/Specify_publishable_lexical_data.htm", "file://D:/FieldWorks_Language_Explorer_Help_Dictionary/User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Publication_Settings_flds/Show_Minor_Entry_Pub_Set_level.htm"&#93; |

## Stale TOC entry (`stale_toc_entries`)

- **Severity:** advisory
- **Owner:** RoboHelp
- **Count:** 1
- **How to fix in RoboHelp:** Open the RoboHelp table of contents, locate the target in Evidence, and retarget or remove the entry before rebuilding the CHM.

| Source or generated path | Problem | Evidence |
| --- | --- | --- |
| `TOC points at a topic that does not exist: User_Interface/Menus/Parser/About_Strata_Sequences_as_a_string_in_the_Hermit_Crab_parser.htm` | TOC points at a topic that does not exist: User_Interface/Menus/Parser/About_Strata_Sequences_as_a_string_in_the_Hermit_Crab_parser.htm | TOC points at a topic that does not exist: User_Interface/Menus/Parser/About_Strata_Sequences_as_a_string_in_the_Hermit_Crab_parser.htm |

## Topic missing from TOC (`not_in_toc`)

- **Severity:** advisory
- **Owner:** RoboHelp
- **Count:** 3
- **How to fix in RoboHelp:** Find the source topic path in RoboHelp and either add it to the appropriate table-of-contents location or remove the orphan topic.

| Source or generated path | Problem | Evidence |
| --- | --- | --- |
| `Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Shoebox_Toobox_style_sort_order.htm` | Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Shoebox_Toobox_style_sort_order.htm | Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Shoebox_Toobox_style_sort_order.htm |
| `User_Interface/Menus/File/Export/Export_Grammar_Sketch.htm` | User_Interface/Menus/File/Export/Export_Grammar_Sketch.htm | User_Interface/Menus/File/Export/Export_Grammar_Sketch.htm |
| `Using_Tools/Lexicon_tools/Lexicon_Edit/Using_Edit_Gram_Infodlg.htm` | Using_Tools/Lexicon_tools/Lexicon_Edit/Using_Edit_Gram_Infodlg.htm | Using_Tools/Lexicon_tools/Lexicon_Edit/Using_Edit_Gram_Infodlg.htm |
