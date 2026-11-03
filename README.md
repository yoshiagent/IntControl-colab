# 智慧型控制：原課程 MATLAB 程式的 Python 筆記本

「[智慧型控制 Intelligent Control](https://yoshiagent.github.io/IntControl/)」課程（約 2005 年的教材）原本以 MATLAB／Simulink 示範。這裡把原課程的 MATLAB 程式與 Simulink 模型改寫成 Python 筆記本，可以直接在 Google Colab 執行，不需要安裝任何軟體。

| 筆記本 | 內容（原課程的檔案） | 對照的網頁 | 開啟 |
|---|---|---|---|
| [遺傳演算法（GA）](notebooks/GA.ipynb) | ga1.m、GA1～GA5 函式、GAExample、MCKPIDGA_Main（GA 調 PID）、MCKFuzzyGa_Main（GA 調模糊控制器） | [網頁](https://yoshiagent.github.io/IntControl/GA.html) | [![在 Colab 開啟](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yoshiagent/IntControl-colab/blob/main/notebooks/GA.ipynb) |
| [粒子群最佳化（PSO）](notebooks/PSO.ipynb) | PSO animations.zip 的四支動畫程式（範例一、二的等高線與 3D 曲面動畫） | [網頁](https://yoshiagent.github.io/IntControl/PSO.html) | [![在 Colab 開啟](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yoshiagent/IntControl-colab/blob/main/notebooks/PSO.ipynb) |
| [類神經網路](notebooks/NN.ipynb) | newp／sim／init／train 指令、NnetAnd.mat（AND 閘）、NetAndmdl.mdl、NetBp.mat 與 NetBpmdl.mdl（倒傳遞網路） | [網頁](https://yoshiagent.github.io/IntControl/NN.html) | [![在 Colab 開啟](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yoshiagent/IntControl-colab/blob/main/notebooks/NN.ipynb) |
| [模糊邏輯工具箱](notebooks/Fuzzy_toolbox.ipynb) | readfis／evalfis／showrule／gensurf 等指令、CreateFIS.m、rmmf／rmvar、tipper.fis／tippersg.fis／tipper0.fis | [網頁](https://yoshiagent.github.io/IntControl/FZ-FuzzyLogicToolbox.html) | [![在 Colab 開啟](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yoshiagent/IntControl-colab/blob/main/notebooks/Fuzzy_toolbox.ipynb) |
| [模糊控制](notebooks/Fuzzy_control.ipynb) | MCK 四種模糊控制器（FuzzyMCK1／2／Sugeno／SugenoL）、水槽液位 sltank.mdl、台車倒單擺 slcp.mdl（含動畫）、fis2sim.mdl | [網頁](https://yoshiagent.github.io/IntControl/FZ.html) | [![在 Colab 開啟](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yoshiagent/IntControl-colab/blob/main/notebooks/Fuzzy_control.ipynb) |
| [PID 控制](notebooks/PID.ipynb) | DCMotorData／DCMotorDataPID.m、直流馬達的三個 Simulink 模型、pid.mdl、mylib／MCKPID／MCKPIDDetail.mdl、數位 PID、Ziegler–Nichols、SISOTool 設計 | [網頁](https://yoshiagent.github.io/IntControl/PID.html) | [![在 Colab 開啟](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yoshiagent/IntControl-colab/blob/main/notebooks/PID.ipynb) |

* 每本筆記本都先列出原本的 MATLAB 程式，再給逐段對應的 Python 版本，並已實際執行（存有輸出與圖）。
* 只用 Colab 內建的 numpy、scipy 與 plotly。
* MATLAB 與 numpy 的亂數序列不同，有隨機性的程式（如 GA）每次結果不會和原講義一模一樣，但演算法相同。
