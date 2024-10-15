# Comparison of Classification Performance of Language Models using Sequence-to-Text Techniques

<br>   
<div align='center'>
<table>
    <thead>
        <tr>
            <th colspan="4"> Team members </th>
        </tr>
    </thead>
    <tbody>
        <tr>
          <tr>
            <td align='center'><a href="https://github.com/mixk0n9"><img src="https://github.com/mixk0n9.png" width="100" height="100"></td>
            <td align='center'><a href="https://github.com/ymk713"><img src="https://github.com/ymk713.png" width="100" height="100"></td>
            <td align='center'><a href="https://github.com/Bluemming"><img src="https://github.com/Bluemming.png" width="100" height="100"></td>
            <td align='center'><a href="https://github.com/iwantpubao"><img src="https://github.com/iwantpubao.png" width="100" height="100"></td>
          <tr>
            <td align='center'>김민경</td>
            <td align='center'>김유미</td>
            <td align='center'>민지현</td>
            <td align='center'>성현수</td>
          </tr>
        </tr>
    </tbody>
</table>

</div>


<!-- Using HTML to center the abstract -->
<div class="columns is-centered has-text-centered">
    <div class="column is-four-fifths">
        <h2>Abstract</h2>
        <div class="content has-text-justified">
 최근 들어 활발한 언어 모형의 개발과 함께 많은 분야의 연구자들이 이에 관심을 갖게 되었다. 
언어 모형의 사용처는 매우 다양하여 많은 분야에 사용될 수 있다. 전통적인 통계학이나 머신러닝의 
분야에서는 기존에 이진 분류에 대한 연구가 활발하게 진행되어왔고, 언어 모형들 역시 동일한 과제를 수행할 
수 있다. 언어 모형의 특징으로 인해 입력 데이터는 테이블 형식의 숫자로 이루어진 데이터가 아니라 
문자형 식의 변수를 요구한다. 이 논문에서는 열 가지의 최신 언어 모형들의 목적과 특징들을 소개한다. 
한편, 언어 모형의 데이터 입력을 위해 시퀀스 데이터를 텍스트로 변환하는 sequence-to-text 방법의 
여러 가지 예시를 구체적으로 제시한다. 이를 통해 언어 모형 구현에 경험이 없는 독자들에게는 도움이 
될 것으로 기대한다. 마지막으로, 제시한 여러 가지 sequence-to-text 방법을 실제 데이터를 이용한 모의 
실험을 통하여 이 논문에서 소개하는 최신 언어 모형들의 성능을 비교하고 머신러닝 모형들의 결과도 
함께 제공하여 언어 모형들의 우수한 분류 성능을 확인한다.
        </div>
    </div>
</div>

---

## Background
The paper "On Computable Numbers, with an Application to the Entscheidungsproblem" was published by Alan Turing in 1936. In this groundbreaking paper, Turing introduced the concept of a universal computing machine, now known as the Turing machine.

## Objective
Turing's main objective in this paper was to investigate the notion of computability and its relation to the Entscheidungsproblem (the decision problem), which is concerned with determining whether a given mathematical statement is provable or not.


## Key Ideas
1. Turing first presented the concept of a "computable number," which refers to a number that can be computed by an algorithm or a definite step-by-step process.
2. He introduced the notion of a Turing machine, an abstract computational device consisting of an infinite tape divided into cells and a read-write head. The machine can read and write symbols on the tape, move the head left or right, and transition between states based on a set of rules.
3. Turing demonstrated that the set of computable numbers is enumerable, meaning it can be listed in a systematic way, even though it is not necessarily countable.
4. He proved the existence of non-computable numbers, which cannot be computed by any Turing machine.
5. Turing showed that the Entscheidungsproblem is undecidable, meaning there is no algorithm that can determine, for any given mathematical statement, whether it is provable or not.

![Turing Machine](/static/image/Turing_machine.png)

*Figure 1: A representation of a Turing Machine. Source: [Wiki](https://en.wikipedia.org/wiki/Turing_machine).*

## Table: Comparison of Computable and Non-Computable Numbers

| Computable Numbers | Non-Computable Numbers |
|-------------------|-----------------------|
| Rational numbers, e.g., 1/2, 3/4 | Transcendental numbers, e.g., π, e |
| Algebraic numbers, e.g., √2, ∛3 | Non-algebraic numbers, e.g., √2 + √3 |
| Numbers with finite decimal representations | Numbers with infinite, non-repeating decimal representations |

He used the concept of a universal Turing machine to prove that the set of computable functions is recursively enumerable, meaning it can be listed by an algorithm.

## Significance
Turing's paper laid the foundation for the theory of computation and had a profound impact on the development of computer science. The Turing machine became a fundamental concept in theoretical computer science, serving as a theoretical model for studying the limits and capabilities of computation. Turing's work also influenced the development of programming languages, algorithms, and the design of modern computers.

## Citation
```
@article{turing1936computable,
  title={On computable numbers, with an application to the Entscheidungsproblem},
  author={Turing, Alan Mathison},
  journal={Journal of Mathematics},
  volume={58},
  number={345-363},
  pages={5},
  year={1936}
}
```

