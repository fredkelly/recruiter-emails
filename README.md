# Crowdsourced Recruiter Emails
Fed up of recruiter SPAM clogging up your inbox? Here's your chance to name and shame those pesky recruiters and enjoy a quiet life.

## Contributing
1. Fork it
2. Add email/s `'nuisance@snappysnapjobs.com' >> emails.txt`
3. Commit changes `git commit -m 'adds annoying person from SnappySnapJobs`
4. Push and submit a pull request evidencing the offending email

## Usage
To convert to an `OR` rule for Google Mail (or similar): `ruby -e "puts File.read('emails.txt').split.join(' OR ')"`
