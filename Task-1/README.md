# Signal & Image Processing | Task-1

- Tasks: [Signal Processing]
  - [Task-1a](#task-1a)
  - [Task-1b](#task-1b)

## Reading/ Prerequisites

The following pre-requites are suggested to be known before starting out with the implementation parts of the task.

Read and learn about them, a write a **small detailed report** about the key understandings in brief for each topic. Explain it as you seem appropriate.

Additionally, perform as instructed for the points in the bracket`[...]`.

---

### TASK-1a

- Signals
  - Continuous Signals, Discrete Signals

  - Time domain, Frequency domain

  - Elementary discrete signals
    - Unit impulse/ Unit sample sequence
    - Unit step sequence
    - Unit ramp sequence
    - Exponential sequences
    - Sinusoidal sequences

    [Graph out the sequences, and include it's mathematical definition]

- Basic operations on discrete-time signals

  - Amplitude scaling

  - Addition

  - Multiplication
  - Time shifting
  - Time scaling
  - Time reversal/ reflection
  - Precedence rule for time-shifting and time-scaling

    [Perform both (a) Time-shifting followed by Time-Scaling, and (b) Time-scaling followed by Time-shifting, and observe and illustrate the differences]

- Systems
  - Properties
    - Linearity property, and it's significance
    - Shift invariance property, and it's significance
    - Memory
    - Causality
    - Stability

  - Linear Shift invariant systems

    - Properties, and Significance

    - Characterisation of LSI systems by its Impulse response

    - Systems in Series (Cascaded LSI systems)

    - Systems in Parallel

      [Assume two LSI systems in general and evaluate the Impusle responses in both cases]

- Filters
  - Types
    - Low Pass Filters
    - High Pass Filters
    - Band Pass Filters
    - Band Stop Filters
  - What characterises a filter?
    - How can filters modify the frequency content of a signal?
  - What is the purpose of a filter in signal processing?
  - Key characteristics of filters
    - Passband
    - Stopband
    - Cutoff frequency
    - Filter order
    - Filter response
  - Finite impulse response (FIR) filters, Infinite impulse response (IIR) filters
    - Limitations and Usage of both

- Convolution
  - Mathematical definition
  - Evaluation methods
    - Manual evaluation
    - Overlap Add method [Bonus]
    - Overlap Save method [Bonus]
    - Computer evaluation [Bonus]
  - Convolution and linear time-invariant (LTI) systems: Study how convolution relates to LTI systems and their properties, including time-invariance, linearity, and causality.
  - Performs convolution between two discrete signals and demonstrate how it combines the input signals to produce the output.

- Fourier analysis

- Nyquist-Shannon Sampling
  - Sampling Theorem

  - Aliasing

  - Wagon-Wheel effect (Stroboscopic effects) [Bonus]

    ![Wagon Wheel effect](https://static.wikia.nocookie.net/revengeristsconsortium/images/2/25/Whee.gif/revision/latest?cb=20141209071330)

- Convolution theorem
  - Fourier transform of the convolution of two signals is equal to the pointwise multiplication of their Fourier transforms.

---

## Programming [Python]

Python has good support for libraries for Signal Processing and Image Processing Applications.

- Accessing and Installations
  - If you're using locally, Download Python from https://www.python.org/downloads/
    - Install the following **libraries**
      - `Numpy`
      - `Scipy`
      - `Pandas`
      - `Matplotlib`
  - Alternatively, Install Anaconda
    - https://www.anaconda.com/download#downloads
      - Available for Windows, macOS (Intel, Apple Silicon), and Linux
    - This install Python, Jupyter Notebook, and most of the other libraries by default.
    - Jupyter Notebooks (https://jupyter.org/)
  - Google Colab
    - https://colab.google/notebooks/
    - https://colab.research.google.com/#create=true
    - Log in using your Google account, and save your Notebooks on Google Drive
- If you're new to Python, checkout the resouces in the next section and complete it before proceeding with the task.

## Programming [MATLAB]

- Install MATLAB

  - Create a **MathWorks account** / Sign in.
    https://login.mathworks.com/embedded-login/landing.html?cid=getmatlab&s_tid=gn_getml

    > Use **Learner ID** to access Campus License.

  - Use MATLAB Online, or run it locally *(recommended)*.

  - Download MATLAB from https://in.mathworks.com/downloads/

  - Login with your MathWorks account while performing MATLAB installation and proceed with the steps. It should automatically detect your **License**.

    - If not, then find your License number at https://in.mathworks.com/mwaccount.

  - Install the following **packages** and **toolboxes**

    - Signal Processing Toolbox
    - Image Processing Toolbox

- If you're new to MATLAB, checkout the resouces in the next section and complete it before proceeding with the task.

---

### TASK-1b

Using either Python or MATLAB (or any other software/ language), perform the following operations.

1. Signal Generation and Visualization

---

**Model solutions** for suitable problems will be available after the due date of the task completion, or an appropriate solution resource will be shared. Check it out at https://github.com/IEEE-EMBS-Manipal/2023-RnP-Signal_ImageProcessing when it's available there.

## Some useful resources

- If you're **new to MATLAB**, check out these resources

  - Introduction to Programming with MATLAB, Coursera

    https://www.coursera.org/learn/matlab

  - MATLAB Tutorial

    https://www.tutorialspoint.com/matlab/index.htm

  - MathWorks: MATLAB Essentials

    https://www.edx.org/course/matlab-essentials

  - INTRODUCTION TO MATLAB FOR ENGINEERING STUDENTS, PDF

    https://www.mccormick.northwestern.edu/documents/students/undergraduate/introduction-to-matlab.pdf

- Introduction to Data, Signal, and Image Analysis with MATLAB, Coursera

  https://www.coursera.org/learn/matlab-image-processing

- Signal processing (scipy.signal)
  https://docs.scipy.org/doc/scipy/reference/signal.html

- Hands On Signal Processing with Python
  https://towardsdatascience.com/hands-on-signal-processing-with-python-9bda8aad39de
- Wagon-wheel effect, WikiMedia
  https://upload.wikimedia.org/wikipedia/commons/e/ef/The_wagon-wheel_effect.ogv
