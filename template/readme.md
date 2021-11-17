# Folder structure
* Minimum template
+ analyses
+ data
+ experiments
+ notes
+ writing / report / text
* Extended template
+ code
+ posters
+ presentations
+ Other necessary / important content
* Highly recommended elements
+ ‘readme.md’ files to guide readers through your project.

# File naming conventions
## Easy readability for machines
    * Avoid spaces:
        + Use underscores (_) to separate different chunks [chunk01_chunk_slug.txt]
        + Use hyphens (-) to separate words in a slug [chunk01_this-is-a-description.txt]
    * Avoid special characters (^.*?+|$) and accents ü → ue 
    * Stick to lowercase characters at all times
## Easy readability for humans
    * Use concise, meaningful slugs (descriptions) and append them to the right-end
    * Do not abbreviate proper names			
## Easy sorting and searching
    * Identify chunks in names with folders in trees
    * Use the minimum necessary chunks per name
    * Never repeat file names; folder names may be repeated across trees
    * Follow paths to order chunks in names accordingly
        + Use prefixes to order files:
            - Numbers preferred instead of letters
            - Left pad with 0 for length consistency
            - Codes may be added to prefixes and must match their folder
            - Keywords may be included to ease searches; might match middle folder names
        + Also dates when needed:
            - Date format ISO 8601: YYYY-MM-DD
            - Use as first identifier to the left to order files chronologically [yyyy-mm-dd_chunk01_slug]

Always be consistent.

## Good examples
    [analyses\main\plotting\subject01\yyyy-mm-dd_plot01_subject01.txt]
    [data\main\clean\subject01\yyyy-mm-dd_clean01_subject01.txt]
    [data\main\raw\recordings\subject01\yyyy-mm-dd_record01_subject01.wav]
## Bad examples
    [analyses\main\plotting\subject01\yyyy-dd-mm_subject01-plot01.txt]
    [data\main\raw\transcripts\subject01\yyyy_mm_dd_raw_trans01_subj01.txt]
