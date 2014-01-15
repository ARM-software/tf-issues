ARM Trusted Firmware Issue Tracker
==================================

This repository is solely for the purpose of creating and tracking issues in
the [ARM Trusted Firmware] repository. It is separate from the main repository
to allow additional users to have push access to issues, while limiting the
number of users with push access to the main repository.

Please follow these guidelines for using the issue tracker:

*   If you have a question, create an [issue] and apply the "question" label.
    If the question is directed at an individual, then assign them to the
    issue. If the question is directed at an organization (e.g. ARM), please
    say so in the description.
*   If you identify a bug, create an [issue] and apply the "bug" label. Clearly
    describe the problem, including steps to reproduce.
*   Before starting work on the main repository, create an [issue] for your
    work, if one does not already exist. This gives everyone visibility of
    your work and helps others avoid working on something similar.
    *   For bugs, apply the "bug" label if it's not already present.
    *   For enhancements, apply the "enhancement" label and clearly describe
        how you intend to implement the change.
    *   Assign yourself to the issue using the drop down box.
*   When the issue has been fixed in the main repository, close the issue. The
    issue may be automatically closed if it is referenced by a git commit
    message (e.g. "fixes arm-software/tf-issues#45").
*   Feel free to comment on any issues with relevant information.
    

Note there is not fine-grained access control on this repository so please do
not edit/close other people's issues without their permission or use this
repository to store code.


[ARM Trusted Firmware]:     https://github.com/ARM-software/arm-trusted-firmware
[issue]:                    https://github.com/ARM-software/tf-issues/issues
