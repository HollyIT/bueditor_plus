BUEditor Plus replaces the default method of selecting which editor to display
with an all new system. Editors are displayed based upon field settings and profiles.

FEATURES:
- Create multiple profiles to control which editor is used.
- Editors are changed on the fly dependent upon input format.
- Assign a different profile to each text field.
- Editor path visibility and element ID disable still works, allowing to help set up
  an alternative editor on each profile.

TO USE:
- Go to admin/modules and enable BUEditor Plus under the Content Authoring category
 (BUEditor is of course required).

- Go to admin/config/content/bueditor and click the "Add new profile" link
- Give your profile a name that makes it easy to identify by you.
- Specify the default and alternative editor for each input format.
- Save the new profile.

Once you have your profiles created, then you need to assign the profiles to the text fields
defined in your entities and bundles.

TO ASSIGN A PROFILE TO THE ARTICLE NODE TYPE:
- Go to admin/structure/types/manage/article
- Click the Edit link for the Body field.
- Under the settings section select the profile you wish to use in the BUEditor Profile select.
  (NOTE: BUEditor will only show on fields that have text processing with this module)