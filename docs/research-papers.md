# Which papers inform skill-based mathematical learning?

This catalogue covers non-LLM research on skill acquisition, cognitive modelling,
mathematical composition, tutoring, and curriculum. Evidence categories distinguish
experiments with human learners from computational demonstrations.

## Pedagogical foundations and human-learning evidence

### The Knowledge-Learning-Instruction Framework: Bridging the Science-Practice Chasm to Enhance Robust Student Learning

- **Authors:** Kenneth R. Koedinger, Albert T. Corbett, Charles Perfetti.
- **Publication:** Cognitive Science, 2012.
- **Evidence:** Pedagogical framework and synthesis of learning research.
- **Relevance:** Connects kinds of knowledge, learning mechanisms, and instructional
  choices. Mathematical primitives and instructionally useful knowledge components
  need not have identical granularity.
- **Source:** [Published article, ERIC copy](https://files.eric.ed.gov/fulltext/ED535880.pdf).

### Learning Factors Analysis – A General Method for Cognitive Model Evaluation and Improvement

- **Authors:** Hao Cen, Kenneth Koedinger, Brian Junker.
- **Publication:** Intelligent Tutoring Systems, 2006.
- **Evidence:** Cognitive-model refinement using student performance data.
- **Relevance:** Combines statistical modelling, expert-defined factors, and search
  to evaluate and refine an initial skill model. Requires learner data; it is not
  a textbook-only skill discovery method.
- **Source:** [Author-hosted paper](https://pact.cs.cmu.edu/koedinger/pubs/Cen%2C%20Koedinger%20%26%20Junker06.pdf).

### Automated Student Model Improvement

- **Authors:** Kenneth R. Koedinger, Elizabeth A. McLaughlin, John C. Stamper.
- **Publication:** Educational Data Mining, 2012.
- **Evidence:** Model search and predictive evaluation across educational datasets.
- **Relevance:** Uses student data to identify weaknesses in knowledge-component
  models. Better predictive fit is distinct from demonstrated instructional benefit.
- **Source:** [LearnLab paper](https://learnlab.org/wp-content/uploads/2016/06/KoedingerMcLaughlinStamperEDM12.pdf).

### Using Data-Driven Discovery of Better Student Models to Improve Student Learning

- **Authors:** Kenneth R. Koedinger, John C. Stamper, Elizabeth A. McLaughlin,
  Tristan Nixon.
- **Publication:** Artificial Intelligence in Education, 2013.
- **Evidence:** Controlled instructional comparison with human learners.
- **Relevance:** Tests a tutor redesign informed by cognitive-model refinement,
  including problem-decomposition planning skills. The findings concern the studied
  geometry unit, not a universal guarantee for skill decomposition.
- **Source:** [Author-hosted paper](https://pact.cs.cmu.edu/pubs/Koedinger%20Stamper%2C%20McLaughlin%20%26%20Nixon.pdf).

## Computational models of skill acquisition and tutor authoring

### The Apprentice Learner architecture: Closing the loop between learning theory and educational data

- **Authors:** Christopher J. MacLellan, Erik Harpstead, Rony Patel,
  Kenneth R. Koedinger.
- **Publication:** Educational Data Mining, 2016.
- **Evidence:** Computational learning models compared with human tutoring data.
- **Relevance:** Makes learning mechanisms executable and compares their predicted
  behavior with observed learner behavior in fraction tutoring environments.
- **Source:** [Conference paper](https://www.educationaldatamining.org/EDM2016/proceedings/paper_118.pdf).

### Integrating representation learning and skill learning in a human-like intelligent agent

- **Authors:** Nan Li, Noboru Matsuda, William W. Cohen, Kenneth R. Koedinger.
- **Publication:** Artificial Intelligence, 2015.
- **Evidence:** Computational skill and representation learning; comparison with
  student learning-curve data.
- **Relevance:** SimStudent learns procedural behavior from examples and feedback.
  The paper exposes representation knowledge as a separate source of hidden
  prerequisites rather than treating operations alone as sufficient.
- **Source:** [Author-hosted article](https://wwcohen.github.io/postscript/simstudent-aij-2014.pdf).
- **Version note:** The file name and online-availability date use 2014; the journal
  issue is dated 2015.

### Decomposed Inductive Procedure Learning: Learning Academic Tasks with Human-Like Data Efficiency

- **Authors:** Daniel Weitekamp, Christopher MacLellan, Erik Harpstead,
  Kenneth Koedinger.
- **Version:** arXiv:2505.10422v1, May 15, 2025.
- **Evidence:** Computational ablations of learning mechanisms in tutoring tasks.
- **Relevance:** Separates learning how to perform an operation, where to bind its
  arguments, and when to apply it. Experiments use supplied primitive functions;
  they do not establish automatic discovery of a complete curriculum from a manual.
- **Source:** [Versioned preprint](https://arxiv.org/abs/2505.10422v1).

### AI2T: Building Trustable AI Tutors by Interactively Teaching a Self-Aware Learning Agent

- **Authors:** Daniel Weitekamp, Erik Harpstead, Kenneth Koedinger.
- **Version:** arXiv:2411.17924v1, November 26, 2024.
- **Evidence:** Rule-induction experiments and a tutor-authoring user study.
- **Relevance:** Learns model-tracing programs from demonstrations and corrective
  feedback. Certainty estimates guide further teaching; these estimates are not
  mathematical proofs of correctness over all inputs.
- **Source:** [Versioned preprint](https://arxiv.org/abs/2411.17924v1).

## Mathematical composition and curriculum benchmarks

### Peano: Learning Formal Mathematical Reasoning

- **Authors:** Gabriel Poesia, Noah D. Goodman.
- **Publication:** Philosophical Transactions of the Royal Society A, 2023.
- **Reading version:** arXiv:2211.15864v1, November 29, 2022.
- **Evidence:** Computational proof search, tactic induction, and curriculum
  experiments with artificial learners.
- **Relevance:** Builds reusable tactics from primitive rules and derives a
  curriculum from their dependencies. The study uses five elementary-algebra
  sections; it is not a human-learning intervention.
- **Sources:** [Versioned preprint](https://arxiv.org/abs/2211.15864v1),
  [published article](https://pmc.ncbi.nlm.nih.gov/articles/PMC10239677/).

### INT: An Inequality Benchmark for Evaluating Generalization in Theorem Proving

- **Authors:** Yuhuai Wu, Albert Qiaochu Jiang, Jimmy Ba, Roger Grosse.
- **Publication:** International Conference on Learning Representations, 2021.
- **Reading version:** arXiv:2007.02924v2, April 3, 2021.
- **Evidence:** Synthetic theorem generation and automated-prover evaluation.
- **Relevance:** Generates algebraic problems with proof witnesses and controls
  aspects of their rule composition. Evaluates prover generalization rather than
  learner mastery or pedagogical effectiveness.
- **Source:** [Versioned paper](https://arxiv.org/abs/2007.02924v2).
