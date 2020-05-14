# Announcements

The Announcements email will serve as a way for anyone in the group to quickly share announcements
that are archived both in GitHub and our Announcements mailing list.

## How to contribute to Announcements

Anyone in the CFDE can contribute by adding comments to [the open
announcements issue in this repository](https://github.com/nih-cfde/announcements/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+Announcements).
The infrastructure team will coordinate the process of assembling the final
email, and distributing it through the Announcements mailing list.

## How to send immediate Announcements

If your announcement is time sensitive, you can submit it to the Announcements mailing list directly by sending
it to Announcements@CFDE.groups.io


## How to send the weekly mail

The current plan is for 'Announcements' emails to be sent on Mondays. An
issue for collecting links will be opened 15 days before the Monday links
email is sent and closed the day the email is sent.

### Step 1. Opening and closing issues

1.  Open an issue in
    [nih-cfde/announcements](https://github.com/nih-cfde/announcements) for collecting
    links. Title it "Announcements to post <two weeks Monday's date>)".
    Add the `Announcements` label. Give it the following text:
    ```
    Add a comment containing your interesting links and announcements here! Let us know under 
    which heading your post belongs (or add your own):

    Critical Announcements
    Events
    Meeting Outcomes
    Resources
    Tools
    New Releases
    Welcome/Farewell
    ```
2.  Keep this issue open 2 weeks.
3.  After 2 weeks, close the issue and repeat steps 1-3.
4.  Proceed to the next steps for creating a pull request and sending
    an email.

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
        collecting the next set of links
    5.  Add a salutation and signature
3.  Check the "Create a new branch for this commit and start a pull
    request" button and click "Propose new file".
4.  Add a commit message and link this pull request to the issue
    containing the links
5.  Assign or mention reviewers who can quickly approve the email.
6.  Incorporate any suggestions then merge the pull request.

### Step 3. Send the email

1.  Using the "view" option for nice rendering, copy the text from the
    `YYYY-MM-DD-announcements.md` file into a [new email on groups.io](https://cfde.groups.io/g/Announcements/post)
2.  Set the subject to "CFDE Announcements"
4.  Send the email to <Announcements@CFDE.groups.io>
