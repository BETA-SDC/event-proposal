# Event Proposals and Materials Repository

[中文](./README.zh.md) | English

> [!IMPORTANT]
> Before creating activities, assigning tasks, or preparing materials, carefully read the [Activities and Publicity in the community repository](https://github.com/BETA-SDC/community/blob/main/docs/procedures/event/README.md). If the activity involves photography, media delivery, or later publicity, also read the [Media Capture Guidelines](https://github.com/BETA-SDC/community/blob/main/docs/procedures/event/media-capture-guidelines.md).

This repository stores traceable records for Beta College SDC activities, from proposals and task assignment to publicity material preparation and message archiving. Activity discussion, task assignment, and notice archiving are handled through Issues and Sub-issues; files such as activity proposals and poster information forms are saved through branches and Pull Requests.

## Repository Structure

| Path | Purpose |
| --- | --- |
| [`.github/ISSUE_TEMPLATE/`](./.github/ISSUE_TEMPLATE/) | Issue templates for activity main Issues, task Sub-issues, message archives, and wrap-up records |
| [`2026-2027/`](./2026-2027/) | Activity materials for the 2026-2027 academic year |
| [`template-for-poster-information.md`](./template-for-poster-information.md) | Poster information collection template |
| [`README.md`](./README.md) | This English guide |
| [`README.zh.md`](./README.zh.md) | Chinese guide |

Common Issue templates:

- [Main activity Issue template](./.github/ISSUE_TEMPLATE/event.yml)
- [Task assignment template](./.github/ISSUE_TEMPLATE/task.yml)
- [Message archive template](./.github/ISSUE_TEMPLATE/message.yml)
- [Activity wrap-up template](./.github/ISSUE_TEMPLATE/wrap-up.yml)
- [Documentation maintenance template](./.github/ISSUE_TEMPLATE/docs.yml)
- [Process improvement template](./.github/ISSUE_TEMPLATE/improvement.yml)
- [Question discussion template](./.github/ISSUE_TEMPLATE/question.yml)

## Standard Workflow

1. Create a main activity Issue in this repository, with the title format `[event] Activity Name`.
2. In the main Issue, explain the activity background, owner, time and location, relevant members, and key deadlines.
3. After entering execution, split poster, registration form, copywriting, venue, material, and other work into Sub-issues, then assign them to corresponding members. Sub-issue titles must include the parent activity name and use ` - `, with spaces on both sides, to separate fields, such as `[task] Activity Name - Task Name`.
4. Create the corresponding branch from the main Issue and prepare the activity proposal, poster information form, notification drafts, and other files on that branch.
5. Submit a Pull Request, link the original Issue, and merge after the owner reviews it.
6. After emails, group notices, or publicity copy are officially sent, create a `[message]` Sub-issue under the corresponding activity main Issue and copy the sent content into it in full.
7. After the activity ends, add participation information, media locations, review notes, and reusable materials.

The full rules are in the [Activities and Publicity](https://github.com/BETA-SDC/community/blob/main/docs/procedures/event/README.md).

## Activity Material Directory Names

Activity materials are usually stored under the corresponding academic year directory, such as [`2026-2027/`](./2026-2027/).

Directory naming format:

```text
YYYY-MM-DD-SERIES-two-digit-session[-specific-topic]
```

Examples:

- [`2026-2027/2026-09-29-BETA-MEET-01-the-field-experience-of-an-ecologist/`](./2026-2027/2026-09-29-BETA-MEET-01-the-field-experience-of-an-ecologist/)
- [`2026-2027/2026-09-09-MATH-HELP-ROOM-01/`](./2026-2027/2026-09-09-MATH-HELP-ROOM-01/)
- [`2026-2027/2026-09-16-GROUP-BIRTHDAY-01-2026-fall/`](./2026-2027/2026-09-16-GROUP-BIRTHDAY-01-2026-fall/)

Series activities use the date, an uppercase series code, and a two-digit session number, such as `2026-09-29-BETA-MEET-01-the-field-experience-of-an-ecologist`. The topic may be omitted when the series name and session number are already clear, such as `2026-09-09-MATH-HELP-ROOM-01`. Non-series activities may use `YYYY-MM-DD-specific-topic`, such as [`2026-2027/2026-09-19-self-study-check-in/`](./2026-2027/2026-09-19-self-study-check-in/).

## Activity Material Files

Each activity directory may contain the following files as needed:

- [`README.md`](./2026-2027/2026-09-29-BETA-MEET-01-the-field-experience-of-an-ecologist/README.md): activity directory overview with a main Issue link
- [`proposal.md`](./2026-2027/2026-09-09-MATH-HELP-ROOM-01/proposal.md): activity proposal or activity description, for example [`2026-2027/2026-09-16-GROUP-BIRTHDAY-01-2026-fall/proposal.md`](./2026-2027/2026-09-16-GROUP-BIRTHDAY-01-2026-fall/proposal.md)
- [`poster-information.md`](./2026-2027/2026-09-09-MATH-HELP-ROOM-01/poster-information.md): poster information form, for example [`2026-2027/2026-09-29-BETA-MEET-01-the-field-experience-of-an-ecologist/poster-information.md`](./2026-2027/2026-09-29-BETA-MEET-01-the-field-experience-of-an-ecologist/poster-information.md)
- [`notification-message.md`](./2026-2027/2026-09-16-GROUP-BIRTHDAY-01-2026-fall/notification-message.md): optional notification copy draft or backup
- [`sign-in/`](./2026-2027/2026-09-16-GROUP-BIRTHDAY-01-2026-fall/sign-in/): sign-in, registration, and participation data directory, for example [`2026-2027/2026-09-16-GROUP-BIRTHDAY-01-2026-fall/sign-in/`](./2026-2027/2026-09-16-GROUP-BIRTHDAY-01-2026-fall/sign-in/)

Different activities only need the files they actually use. Do not create empty files just to match this list.

## Poster Information

> [!IMPORTANT]
> When a poster is needed, first create a poster task Sub-issue under the corresponding activity main Issue, assign it to the executor, and @ the activity owner or publicity owner. Images, QR codes, reference images, and other materials should be attached to the Sub-issue instead of being left only in chat records.

When filling in poster information, use [`template-for-poster-information.md`](./template-for-poster-information.md) and make sure the following items are complete:

- Chinese and English activity names
- Organizer, partners, or other organizations that need to appear
- Date, time, location, and activity format
- Registration method, registration link, or registration QR code
- Contact person or activity contact group
- Activity introduction and information to emphasize
- Specific image, logo, guest photo, QR code, or other material notes

## Message Archiving

Message archiving does not mean placing the copy randomly in a file. It means creating a `[message]` Sub-issue under the corresponding activity main Issue and copying the officially sent email, group notice, or publicity copy into it in full.

At minimum, record:

- Full content of the sent copy
- Sending channel
- Sending time
- Sender or owner
- Screenshots, links, or recipient scope notes

## References

- [Activities and Publicity](https://github.com/BETA-SDC/community/blob/main/docs/procedures/event/README.md)
- [Media Capture Guidelines](https://github.com/BETA-SDC/community/blob/main/docs/procedures/event/media-capture-guidelines.md)
- [community Documentation Center](https://github.com/BETA-SDC/community/blob/main/docs/README.md)
- [GitHub Help and Reference Materials](https://github.com/BETA-SDC/community/blob/main/docs/resources/README.md)
