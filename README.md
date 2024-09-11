# NLP_2024

{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": [],
      "toc_visible": true,
      "include_colab_link": true
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "view-in-github",
        "colab_type": "text"
      },
      "source": [
        "<a href=\"https://colab.research.google.com/github/realbro1123/NLP_2024/blob/main/1_CodeCells_Basic.ipynb\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "#🐹 🐾  Code cells\n",
        "\n",
        "1️⃣  When you write code lines with python, you use code cells. You can insert a new code cell by selecting +Code. it can be move around with an <font color='red'>arrow-up</font> ⬆️ symbol and an <font color='red'>arrow-down</font> ⬇️ symbol at the right top corner of each code cell. You can also delete it by selecting the trash can symbol.   \n",
        "\n",
        "2️⃣ No indent vs. Indent\n",
        "\n",
        "- ✔️ Do not indent when you write code lines on code cells.\n",
        "\n",
        "- ✔️ When you define a function, the first line of the function ends with a colone symbol (i.e., :).\n",
        "- ✔️ In order to indicate following code lines are part of a function defined, you use indent.\n",
        "\n",
        "3️⃣ Code lines including different code cells can be directly interconnected. If you having any error message related to missing variables, functions, modules, or packages, etc., simply run code cells in order.\n",
        "\n",
        "4️⃣  Misc: Run & Remove\n",
        "- Click on ▶️  (Run Cell) to **execute** code lines.\n",
        "- Click on ❌  (Remove) to **delete** restuls."
      ],
      "metadata": {
        "id": "ttlPtPfmAAdV"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "## <font color = 'green'> Creating & running code cells, arrow-up, and arrow-down\n",
        "\n"
      ],
      "metadata": {
        "id": "aJ0Z8qFlWaAx"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "#@markdown 🐣 Define variable a\n",
        "\n",
        "a = 1"
      ],
      "metadata": {
        "id": "xV1LWOHyWZaq"
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "#@markdown 🐣 Define variable b\n",
        "b = 2"
      ],
      "metadata": {
        "id": "Kggbn20yVpFO"
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "#@markdown 🐣 Use a print function and a Boolean operator +\n",
        "print(a + b)"
      ],
      "metadata": {
        "id": "oC2orsLTWQwg",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "6e402333-33eb-4ff6-ed16-18a326fda4de"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "3\n"
          ]
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "## <font color = 'green'> Deleting a code cell"
      ],
      "metadata": {
        "id": "zSushYscXEkk"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "#@markdown 🐣 Delete a current code cell -> click the trash can symbol\n",
        "\n",
        "c = 3\n",
        "print (c)"
      ],
      "metadata": {
        "id": "DxeSoiafXW0z",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "c1582abf-c66f-40c5-d259-a77e45e80673"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "3\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#@markdown 🐣 Use a print function and a Boolean operator -\n",
        "print(c-b)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "_1keJy7BFboH",
        "outputId": "b910bba2-f15a-4e9d-ffbf-d1666172c1b6"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "1\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "#@markdown 🐣 A new variable name overlapped with a revious variable name overwrite the old one.\n",
        "a=100\n",
        "print (a+b)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "rgKSEjNxF9LH",
        "outputId": "7d8b4fe9-a417-4281-d62b-1193515f374b"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "102\n"
          ]
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "## A variable can begin with any **alphabets** or an **underscore**.\n",
        "\n",
        "### ⛔  Warning\n",
        "i) Using the names for installed functions such as **abs()**, you can no loner use the original function named **abs( )**.\n",
        "\n",
        "ii) No use whatsoever;\n",
        "- a) 😱 <font color = 'green'> no digit-initial varialbe </font>\n",
        "- b) 😱 <font color = 'green'>no Python statements (e.g., if, elif, while, for, def, class, and, etc.) </font>\n",
        "\n",
        "## ⛔ Avoid preassigned keywords!"
      ],
      "metadata": {
        "id": "81wq2eHidJ0N"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "import keyword\n",
        "keyword.kwlist"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "movI84aVdemJ",
        "outputId": "f777a7cf-4502-4c35-8918-8a523845a1d7"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "['False',\n",
              " 'None',\n",
              " 'True',\n",
              " 'and',\n",
              " 'as',\n",
              " 'assert',\n",
              " 'async',\n",
              " 'await',\n",
              " 'break',\n",
              " 'class',\n",
              " 'continue',\n",
              " 'def',\n",
              " 'del',\n",
              " 'elif',\n",
              " 'else',\n",
              " 'except',\n",
              " 'finally',\n",
              " 'for',\n",
              " 'from',\n",
              " 'global',\n",
              " 'if',\n",
              " 'import',\n",
              " 'in',\n",
              " 'is',\n",
              " 'lambda',\n",
              " 'nonlocal',\n",
              " 'not',\n",
              " 'or',\n",
              " 'pass',\n",
              " 'raise',\n",
              " 'return',\n",
              " 'try',\n",
              " 'while',\n",
              " 'with',\n",
              " 'yield']"
            ]
          },
          "metadata": {},
          "execution_count": 7
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "### ⏰ For more detailed and extensive information, visit [Overview of Colaboratory Features](https://colab.research.google.com/notebooks/basic_features_overview.ipynb)"
      ],
      "metadata": {
        "id": "zy4PTJNVg17p"
      }
    }
  ]
}
