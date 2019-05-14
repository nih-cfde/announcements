# Announcements

## Rationale

The announcements email will serve as a way for anyone in the group to quickly share announcements
that are archived both in GitHub and our Announcements mailing list.

## How to contribute

Anyone in the CFDE can contribute by adding comments to [the open
issue in this repository](https://github.com/nih-cfde/announcements/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+Announcements).
The infrastructure team will coordinate the process of assembling the final
email, which is automatically sent by the Announcements list on merge.



## How to send the weekly mail

The current plan is for 'Announcements' emails to be sent on Monday. An
issue for collecting links will be opened 8 days before the Monday links
email is sent and closed the day before the email is sent.

### Step 1. Opening and closing issues

1.  Open an issue in
    [nih-cfde/announcements](https://github.com/nih-cfde/announcements) for collecting
    links. Title it "Weekly announcements to post <next Monday's date>)".
    Add the `Announcements` label.
2.  Keep this issue open one week.
3.  After 1 week, close the issue and repeat steps 1-3.
4.  Proceed to the next steps for creating a pull request and sending
    and email.

### Step 2. Create pull request with links assembled into email format

The links deposited in an issue will need to be assembled into a single
document for distribution.

1.  Create a new file called `YYYY-MM-DD-announcements.md` in [the
    announcements repo of
    nih-cfde](https://github.com/nih-cfde/announcements)
2.  Populate the file with content
    1.  Paste all the links from the appropriate issue
    2.  Organize the links into sections (e.g. tools & resources,
        events)
    3.  Add a sentence for context
    4.  Add a concluding sentence pointing the reader to an issue for
        collecting next week's links
    5.  Add a salutation and signature
3.  Check the "Create a new branch for this commit and start a pull
    request" button and click "Propose new file".
4.  Add a commit message and link this pull request to the issue
    containing the links
5.  Assign or mention reviewers who can quickly approve the email.
6.  Incorporate any suggestions then merge the pull request.
7.  Include the entire, formatted, text of the email as your commit message
8.  Groups.io will automatically get the email upon merge
9.  Double check that the email looks good (it's moderated) and approve via Groups.io
