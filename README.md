# ScikitLearn-ExplorAndContrib

This is the design archive for CSCD01, a 4th-year CS course at the University of Toronto, offered during the Winter 2021 term.

> [CSCD01H3: Engineering Large Software Systems](https://utsc.calendar.utoronto.ca/course/cscd01h3), An introduction to the theory and practice of large-scale software system design, development, and deployment. Project management; advanced UML; requirements engineering; verification and validation; software architecture; performance modeling and analysis; formal methods in software engineering.

**Our Goal**

Our team aims to contribute to scikit-learn by addressing the following five issues from their GitHub repository:

| Easy level                                                   | Medium level                                                 | Hard feature                                                 |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [#18837](https://github.com/scikit-learn/scikit-learn/issues/18837), [#11209](https://github.com/scikit-learn/scikit-learn/issues/11209) | [#597](https://github.com/scikit-learn/scikit-learn/issues/597), [#14257](https://github.com/scikit-learn/scikit-learn/issues/14257) | [#18968](https://github.com/scikit-learn/scikit-learn/issues/18968) |

**Our Strengths** 

- [#18837](https://github.com/scikit-learn/scikit-learn/issues/18837): This issue focuses on fixing problems with default kwarg in most functions in `scipy.linalg`. We are skilled in debugging code, so we anticipate minimal difficulties in inspecting the codebase to identify the modules requiring changes.

- [#11209](https://github.com/scikit-learn/scikit-learn/issues/11209): This issue involves implementing the Imputation transformer to complete missing values in a matrix. We find the description of the imputation strategy and parameters straightforward.

- [#597](https://github.com/scikit-learn/scikit-learn/issues/597): We have taken algorithm courses that equip us with clear reasoning for addressing this issue. Additionally, we are familiar with the data structures mentioned.

- [#14257](https://github.com/scikit-learn/scikit-learn/issues/14257): This feature request aims to combine `TimeSeriesSplit` (which provides train indices) with the group awareness of other cross-validation strategies. We chose this feature because existing cross-validation split strategies can serve as useful references for developing and testing.

- [#18968](https://github.com/scikit-learn/scikit-learn/issues/18968): This new feature will allow NaN values to pass through `OrdinalEncoder`, which currently cannot be fitted with NaNs. We selected this feature because it likely encounters issues similar to those in [#579](https://github.com/scikit-learn/scikit-learn/issues/579), which we have previously examined.

**Team**

Zhifei Song   songzhif  [soso.song@mail.utoronto.ca](mailto:soso.song@mail.utoronto.ca)

Kevin Zhu    zhukevi6  [kaiwen.zhu@mail.utoronto.ca](mailto:kaiwen.zhu@mail.utoronto.ca)

Yifei Gao    gaoyife5  [yiffy.gao@mail.utoronto.ca](mailto:yiffy.gao@mail.utoronto.ca)

Chunang Xu   xuchunan  [chunang.xu@mail.utoronto.ca](mailto:chunang.xu@mail.utoronto.ca)

Xinzheng Xu   xuxinzhe  [xinzheng.xu@mail.utoronto.ca](mailto:xinzheng.xu@mail.utoronto.ca)

Shu-Shian Wang wangs314  [shushuan.wang@mail.utoronto.ca](mailto:shushuan.wang@mail.utoronto.ca)
