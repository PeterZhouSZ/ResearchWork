**Vocabulary Tree VS VS MIRROR**

**N_tm**: number of tried matches

**N_gv**: number of passed geometric verification

**N_fm**: number of final correspondences

<table>
    <tr>
        <th rowspan="2" colspan="2">Dataset</th>
        <th rowspan="2">Images</th>
        <th colspan="4">Vocabulary Tree</th>
        <th colspan="4">MIRROR</th>
    </tr>
    <tr>
        <th>Cam</th>
        <th>R_mst</th>
        <th>R_te</th>
        <th>R_gr</th>
        <th>RE</th>
        <th>Cam</th>
        <th>R_mst</th>
        <th>R_te</th>
        <th>R_gr</th>
        <th>RE</th>
    </tr>
    <tr>
        <td rowspan="9">Ambiguous Datasets</td>
    </tr>
    <tr>
        <td>Books</td>
        <td>21</td>
        <td>21</td>
        <td>20/20(1.0)</td>
        <td>98/122(0.803)</td>
        <td>127/221(0.575)</td>
        <td>0.396</td>
        <td>21</td>
        <td>19/19(1.0)</td>
        <td>51/56(0.911)</td>
        <td>84/199(0.422)</td>
        <td>0.404</td>
    </tr>
    <tr>
        <td>Cereal</td>
        <td>25</td>
        <td>24</td>
        <td>21/21(1.0)</td>
        <td>64/70(0.914)</td>
        <td>88/311(0.283)</td>
        <td>0.835</td>
        <td>25</td>
        <td>22/22(1.0)</td>
        <td>72/80(0.900)</td>
        <td>97/254((0.382)</td>
        <td>0.576</td>
    </tr>
    <tr>
        <td>Cup</td>
        <td>64</td>
        <td>64</td>
        <td>62/65(0.954)</td>
        <td>270/387(0.698)</td>
        <td>299/697(0.429)</td>
        <td>0.448</td>
        <td>13</td>
        <td>60/63(0.952)</td>
        <td>170/194(0.876)</td>
        <td>209/573(0.365)</td>
        <td>0.436</td>
    </tr>
    <tr>
        <td>Desk</td>
        <td>31</td>
        <td>31</td>
        <td>28/28(1.0)</td>
        <td>90/94(0.957)</td>
        <td>167/461(0.362)</td>
        <td>0.490</td>
        <td>31</td>
        <td>29/30(0.967)</td>
        <td>119/151(0.788)</td>
        <td>145/326(0.445)</td>
        <td>0.476</td>
    </tr>
    <tr>
        <td>Forbiden city</td>
        <td>150</td>
        <td>15</td>
        <td>139/146(0.952)</td>
        <td>522/614(0.850)</td>
        <td>677/7288(0.093)</td>
        <td>0.296</td>
        <td>12</td>
        <td>133/152(0.875)</td>
        <td>364/391(0.931)</td>
        <td>650/10976(0.059)</td>
        <td>0.446</td>
    </tr>
    <tr>
        <td>Indoor</td>
        <td>153</td>
        <td>38</td>
        <td>143/150(0.953)</td>
        <td>373/443(0.842)</td>
        <td>500/6333(0.079)</td>
        <td>0.427</td>
        <td>72</td>
        <td>131/140(0.936)</td>
        <td>341/381(0.895)</td>
        <td>379/11612(0.033)</td>
        <td>0.448</td>
    </tr>
    <tr>
        <td>oats</td>
        <td>24</td>
        <td>24</td>
        <td>21/23((0.913)</td>
        <td>64/66(0.970)</td>
        <td>165/278(0.594)</td>
        <td>0.379</td>
        <td>24</td>
        <td>21/21(1.0)</td>
        <td>52/55(0.945)</td>
        <td>66/277(0.238)</td>
        <td>0.326</td>
    </tr>
    <tr>
        <td>Street</td>
        <td>19</td>
        <td>6</td>
        <td>17/19(0.895)</td>
        <td>38/45(0.844)</td>
        <td>48/162(0.296)</td>
        <td>0.371</td>
        <td>19</td>
        <td>17/18(0.944)</td>
        <td>47/49(0.959)</td>
        <td>59/173(0.341)</td>
        <td>0.560</td>
    </tr>
    <tr>
        <td rowspan="5">COLMAP Dataset</td>
    </tr>
    <tr>
        <td>Gerrard Hall</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>Person Hall</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>South Building</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
    <tr>
        <td>Graham Hall - Interior</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
    </tr>
</table>