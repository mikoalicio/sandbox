# MIK Sandbox
MI Koalíció - Sandbox
Közösségi projekteket támogató repository
(nem hivatalos, tesztelési céllal létrehozott tudástár)


MI Koalíció - Sandbox tartalom

Nyelvi modellek
- Hilanco-GPTX
HILANCO = A HILANCO egy magyarországi természetes nyelvfeldolgozási konzorcium (NLP), amely a Magyar Nyelvtudományi Kutatóközpont (NYTK) és a Pécsi Tudományegyetem Alkalmazott Adattudományi és Mesterséges Intelligencia Központ (PTE) között jött létre.
https://hilanco.github.io 
   - 6.7 milliárd paraméteres GPT-NEOX változat, amelyet a The Pile adathalmazzal előtanítottunk
   - The Pile dataset itt érhető el > https://pile.eleuther.ai
   - Az "inference checkpoint" innen tölthető le (13,4 GB) > https://polka.nytud.hu/slim
   - a tréning és a finomhangolás ellenőrzőpontja pedig innen (95 GB) > https://polka.nytud.hu/full
   - A modellt "Bolka" nevű DGX-A100 szerveren képeztük ki.

<update: 2022.06.11>
- Hilanco-GPTX Angol-MAGYAR(!) model
   - Tesztelhető az alábbi linken: https://juniper.nytud.hu/demo/gpt3
   - Teszteléshez segítség az alábbi oldalakon:
    - https://github.com/dataandai/Hungarian-gpt-3/wiki
    - https://github.com/dataandai/Hungarian-gpt-3
