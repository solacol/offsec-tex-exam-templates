# Offensive Security TeX Exam Templates 
- Just because `LaTeX` > `Word`/`LibreOffice` etc.
- Templates are more or less dirty, so not perfect and definitively not clean `tex` ... shame on me.
- Templates contains examples for common stuff, like listings, tables and figures
- Structure is not completely the same as in the original templates, so feel free to adjust as needed

### IMPORTANT - README
According to Offensive Security copyright, it has to be asked for permission to share parts etc. of the template or similar. After asking for permission to do so, the final result is, that I'm free to share my template as long s it doesn't contain any OffSec logos or copyright information.

This means, at least in my mind, I can provide a template with placeholders (here: orange `todos`). I've tried to make it as easy as possible, so that everybody can just replace the files and placeholders as needed. Logos can be extracted by just using the most recent OffSec `Word/LibreOffice` templates and saving the images as `img/default/head.png` and `img/default/mid.png`

## OSWP
- [Exam Guide](https://help.offensive-security.com/hc/en-us/articles/360046904731-OSWP-Exam-Guide)
- [Original Template (Word)](https://www.offensive-security.com/wifu/OSWP-Exam-Report.docx)
- [Original Template (LibreOffice)](https://www.offensive-security.com/wifu/OSWP-Exam-Report.odt)

## OSCP
- [Exam Guide](https://help.offensive-security.com/hc/en-us/articles/360040165632-OSCP-Exam-Guide)
- [Original Template (Word)](https://www.offensive-security.com/pwk-online/OSCP-Exam-Report.docx)
- [Original Template (LibreOffice)](https://www.offensive-security.com/pwk-online/OSCP-Exam-Report.odt)

## OSWA
- [Exam Guide](https://help.offensive-security.com/hc/en-us/articles/4410105650964-OSWA-Exam-Guide)
- [Original Template (Word)](https://www.offensive-security.com/oswa-online/OSWA-Exam-Report.docx)
- [Original Template (LibreOffice)](https://www.offensive-security.com/oswa-online/OSWA-Exam-Report.odt)

## OSDA
- [Exam Guide](https://help.offensive-security.com/hc/en-us/articles/4410105675412-OSDA-Exam-Guide)
- [Original Template (Word)](https://offensive-security.com/osda-online/OSDA-Exam-Report.docx)
- [Original Template (LibreOffice)](https://offensive-security.com/osda-online/OSDA-Exam-Report.odt)

## OSED
- [Exam Guide](https://help.offensive-security.com/hc/en-us/articles/360052977212-OSED-Exam-Guide)
- [Original Template (Word)](https://www.offensive-security.com/osed-online/OSED-Exam-Report.docx)
- [Original Template (LibreOffice)](https://www.offensive-security.com/osed-online/OSED-Exam-Report.odt)

## OSWE
- [Exam Guide](https://help.offensive-security.com/hc/en-us/articles/360046869951-OSWE-Exam-Guide)
- [Original Template (Word)](https://www.offensive-security.com/awae/OSWE-Exam-Report.docx)
- [Original Template (LibreOffice)](https://www.offensive-security.com/awae/OSWE-Exam-Report.odt)

## OSEP
- [Exam Guide](https://help.offensive-security.com/hc/en-us/articles/360050293792-OSEP-Exam-Guide)
- [Original Template (Word)](https://www.offensive-security.com/osep-online/OSEP-Exam-Report.docx)
- [Original Template (LibreOffice)](https://www.offensive-security.com/osep-online/OSEP-Exam-Report.odt)

## OSMR
- [Exam Guide](https://help.offensive-security.com/hc/en-us/articles/4411107766804-OSMR-Exam-Guide)
- [Original Template (Word)](https://www.offensive-security.com/osmr-online/OSMR-Exam-Report.docx)
- [Original Template (LibreOffice)](https://www.offensive-security.com/osmr-online/OSMR-Exam-Report.odt)

## OSEE
- [Exam Guide](https://help.offensive-security.com/hc/en-us/articles/360046458732-OSEE-Exam-Guide)
- [Exam Template (Word)](https://offensive-security.com/awe/AWE-Exam-Report.docx)

## Archive
- Not needed anymore, but here for sake of completeness and nostalgia.

### OSCE (retired on 15/10/2020)
- [Course Info](https://www.offensive-security.com/ctp-osce/)

## Usage
- Use a fully loaded `LaTeX` IDE (do not forget the `tex` distribution) with lots of fancy features and bullsh_t ;)
- Replace placeholders (here: orange `todos`) with the corresponding parts of the original template
- Replace images `head.png` and `mid.png` with the corresponding ones of the original template
- Define your personal data in `ABCD-OS-XXXXX-Exam-Report.tex`

```tex
%
% DEFINE PERSONAL DATA
%
\newcommand{\OSID}{OS-XXXXX}
\newcommand{\MAIL}{john.doe@example.org}
\newcommand{\NAME}{John Doe}
```

- Set the number to fit your exam in `ABCD-OS-XXXXX-Exam-Report.tex`, e.g. `2` for `OSCP`

```tex
% DEFINE EXAM DATA (choose number)
%
%   0     Default
%   1     OSWP
%   2     OSCP
...
%   42    OSEE
%
\newcommand{\EXAM}{2}
```

- Use the `img` folder for screenshots etc. (just a recommendation)
- Put your exam notes aka report in the corresponding file for your exam, e.g. `OSWE` can be found here: `exam/oswe/oswe.tex`
- Compile and be happy
- **Do not forget:**
    - Change file name `ABCD-OS-XXXXX-Exam-Report.tex` (`ABCD` and `XXXXX`) to fit your exam and OSID, e.g. for `OSCP` change it to `OSCP-OS-12345-Exam-Report.tex` (make sure it fits the exam requirements)

# NOTE
- Use at your `own risk`!
- `No guarantees` if reports written by usage of the templates in this repo will fail to fulfill any requirements!

# TODOs
- Table of figures etc.
- Title page pimp
- Appendix
- Clean up packages
- Make it more professional ^^ 
- Some more error checks
