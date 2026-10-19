md_text = """# Disagreement Examples

## Example 1 — robotology/ycm (ActivityPattern)

**Participants:** afink12 and bxy539

**Author:** Irregular

**Validator:** Declining

**Reason:** Activity slows down following a large spike.

**Resolution:** ValidatorKept

## Example 2 — geostat-framework/gstools (RecentThemes)

**Participants:** afink12 and bpatel

**Author:** Bug fixes:Release

**Validator:** Bug fixes:Documentation updates

**Reason:** Recent commits show bug fixes and documentation changes.

**Resolution:** ValidatorKept

## Example 3 — juliaearth/geostats.jl (RecentThemes)

**Participants:** afink12 and bpatel

**Author:** Release:Automated bot contributions

**Validator:** Release:Documentation updates

**Reason:** Commit author information identifies bot contributions.

**Resolution:** AuthorKept
"""

with open("bpatel_disagreement_examples.md", "w", encoding="utf-8") as file:
    file.write(md_text)

print("Markdown file created successfully!")