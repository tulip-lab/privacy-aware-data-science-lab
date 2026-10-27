[![GitHub issues](https://img.shields.io/github/issues/tulip-lab/privacy-aware-data-science-lab)](https://github.com/tulip-lab/privacy-aware-data-science-lab/issues) [![GitHub pull requests](https://img.shields.io/github/issues-pr/tulip-lab/privacy-aware-data-science-lab)](https://github.com/tulip-lab/privacy-aware-data-science-lab/pulls) [![GitHub stars](https://img.shields.io/github/stars/tulip-lab/privacy-aware-data-science-lab.svg?style=social&label=Star)](https://github.com/tulip-lab/privacy-aware-data-science-lab/stargazers/) [![Course portal](https://img.shields.io/badge/course-Privacy_aware_Data_Science-1f6feb?logo=github)](https://github.com/tulip-lab/privacy-aware-data-science)

---

![TULIP Lab FLIP — Fundamentals of Learning and Intelligent Processing](https://raw.githubusercontent.com/tulip-lab/pattern-classification-lab/0cad4beb88a60a3b8d288f45b35c17d7ade4381a/Assets/images/flip-banner.png)

# FLIP: Privacy-aware Data Science Lab

**FLIP** stands for **Fundamentals of Learning and Intelligent Processing**.
This is the practical companion to
[Privacy-aware Data Science](https://github.com/tulip-lab/privacy-aware-data-science).
Use the course portal for concepts, lecture handouts, learning outcomes,
references and offering information.

> The first two PaDS practicals are planned around existing public Modern Data
> Science / SIT742 exercises. Their guides link to recorded upstream versions;
> no PaDS notebooks or tested PaDS runtime are hosted here yet.

## Start here

- Choose an activity from the [practical catalogue](#practical-catalogue).
- Review its prerequisites, learning purpose and expected evidence.
- Follow the [notebook setup guidance](#notebook-environments).
- Check [assessment and submission guidance](#assessment-and-submission) before
  treating any activity as assessed work.

## How to work through the labs

1. Read the corresponding conceptual session in the course portal.
2. Open the practical guide and then the linked source notebook.
3. Run the supplied baseline before changing parameters or adding queries.
4. Record the data source, public bounds, privacy parameters and budget use.
5. Retain your experiment results and explain their limitations.

The initial path starts with private exploration and accounting, then moves to
private classification. Folder names follow the course's stable S00–S17
sessions. Practical IDs such as S05A and S13A are content identifiers, not weeks.

## Practical catalogue

| Session | Topic | Practical guide | Availability |
| :---: | --- | --- | --- |
| S05 | Composition | [S05A — Private exploration and budget accounting](S05-Composition/README.md) | Planned PaDS activity; upstream M06B notebook available |
| S13 | DP Learning | [S13A — Private Naive Bayes and utility](S13-DPLearning/README.md) | Planned PaDS activity; upstream M06A notebook available |

Other course sessions do not yet have a PaDS practical listed. The shared
notebooks remain maintained upstream; this repository currently provides links
and PaDS learning guidance rather than duplicate notebook copies.

## Notebook environments

- **Google Colab / online:** follow the source notebook's online setup option.
- **Local Jupyter:** follow the source notebook's local environment instructions.

There is no repository-wide PaDS installation command yet. The linked
notebooks retain their SIT742 context and have not been re-executed for PaDS.

## Data and learning evidence

S13A uses the public Iris teaching dataset. S05A uses public Covertype data or a
labelled synthetic fallback. Record which source was used and distinguish a
code-flow demonstration from findings about a real dataset.

Use public or synthetic data for these activities. Follow the source's content,
code and dataset notices when adapting materials. Keep credentials, student
records and private teaching material out of public notebooks and issues.

## Assessment and submission

These practical guides describe learning activities. Current assessment dates,
submission routes, collaboration rules and grading requirements come from the
relevant offering; consult the
[course portal](https://github.com/tulip-lab/privacy-aware-data-science#assessment-and-offerings)
and your teaching team.

Do not submit assessed work through public issues or pull requests unless your
assignment instructions explicitly require that method. Instructor solutions
and internal marking material are maintained separately.

## Contributing

Report practical corrections through the
[issue tracker](https://github.com/tulip-lab/privacy-aware-data-science-lab/issues).
Keep improvements focused, preserve session IDs, and describe any checks
performed. A planned activity should only be marked runnable after its notebook
and setup have been tested.

## Related materials

- [PaDS course portal](https://github.com/tulip-lab/privacy-aware-data-science)
- [Modern Data Science](https://github.com/tulip-lab/modern-data-science)
- [SIT742 practical collection](https://github.com/tulip-lab/SIT742)
- [PaDS lecture handouts](https://github.com/tulip-lab/handouts/tree/main/PaDS)

Point of contact: [Prof. Gang Li](https://github.com/tuliplab).

Prepared by :tulip: **[TULIP Lab](https://www.tulip.academy), Australia**
