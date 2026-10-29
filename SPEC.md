# Job Matcher: Spec (v1)

**One line:** Upload your resume in Arabic or English and get the 20 best-fit open Summer 2027 internships, each flagged for citizenship/sponsorship limits and explained.

## User
F-1 international and Saudi CS students looking for Summer 2027 internships in the U.S.

## Job to be done
Upload a resume (PDF, DOCX or text; Arabic or English) and get:
- the 20 best-fit open internships, ranked
- a flag on each one that requires U.S. citizenship or won't sponsor
- on click, a short reason why it fits and what's missing

## Success metrics
1. **Match quality:** NDCG@10 ≥ 0.60 on the locked test set (Step 9/10)
2. **Adoption:** 25+ real users by Feb 14, 2027
3. **Helpfulness:** ≥ 60% of rated matches get a thumbs up

## Out of scope for v1
- Workday postings with full descriptions (no public API; title only)
- Full-time or non-internship roles
- Auto-apply, cover letters, resume rewriting
- Mobile app (responsive web only)
- Payments or premium features
- Countries other than the U.S.
