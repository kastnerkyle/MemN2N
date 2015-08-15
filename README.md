## End-To-End Memory Networks
This is a Theano implementation of [End-To-End Memory Networks](http://arxiv.org/abs/1503.08895v4), formerly known as Weakly Supervised Memory Networks. The dataset can be found [here](http://fb.ai/babi).

Below are the results obtained from the current implementation on [the set of toy tasks](http://arxiv.org/abs/1502.05698).

<table>
    <thead>
        <tr>
            <th></th>
            <th colspan="2">MemN2N (Sukhbaatar 2015)</th>
            <th colspan="2">This Repo</th>
        </tr>
        <tr>
            <th>Task#</th>
            <th>BoW</th>
            <th>PE</th>
            <th>BoW</th>
            <th>PE</th>
        </tr>
    </thead>
    <tbody>
        <tr><td>1</td>
        
            <td>0.6</td>
            <td></td>
            
            <td>37.6</td>
            <td></td>
            
        </tr>
        <tr><td>2</td>
        
            <td>17.6</td>
            <td></td>
            
            <td>49.1</td>
            <td></td>
            
        </tr>
        <tr><td>3</td>
        
            <td>71.0</td>
            <td></td>
            
            <td>77.8</td>
            <td></td>
            
        </tr>
        <tr><td>4</td>
        
            <td>32.0</td>
            <td></td>
            
            <td>31.4</td>
            <td></td>
            
        </tr>
        <tr><td>5</td>
        
            <td>18.3</td>
            <td></td>
            
            <td>23.5</td>
            <td></td>
            
        </tr>
        <tr><td>6</td>
        
            <td>8.7</td>
            <td></td>
            
            <td>27.9</td>
            <td></td>
            
        </tr>
        <tr><td>7</td>
        
            <td>23.5</td>
            <td></td>
            
            <td>N/A</td>
            <td></td>
            
        </tr>
        <tr><td>8</td>
            
            <td>11.4</td>
            <td></td>
            
            <td>N/A</td>
            <td></td>
            
        </tr>
        <tr><td>9</td>
        
            <td>21.1</td>
            <td></td>
            
            <td>19.5</td>
            <td></td>
            
        </tr>
        <tr><td>10</td>
        
            <td>22.8</td>
            <td></td>
            
            <td>26.1</td>
            <td></td>
            
        </tr>
        <tr><td>11</td>
        
            <td>4.1</td>
            <td></td>
            
            <td>30.1</td>
            <td></td>
            
        </tr>
        <tr><td>12</td>
        
            <td>0.3</td>
            <td></td>
            
            <td>52.2</td>
            <td></td>
            
        </tr>
        <tr><td>13</td>
            
            <td>10.5</td>
            <td></td>
            
            <td>46.0</td>
            <td></td>
            
        </tr>
        <tr><td>14</td>
        
            <td>1.3</td>
            <td></td>
            
            <td>21.8</td>
            <td></td>
            
        </tr>
        <tr><td>15</td>
            
            <td>24.3</td>
            <td></td>
            
            <td>0.0</td>
            <td></td>
            
        </tr>
        <tr><td>16</td>
        
            <td>52.0</td>
            <td></td>
            
            <td>55.5</td>
            <td></td>
            
        </tr>
        <tr><td>17</td>
        
            <td>45.4</td>
            <td></td>
            
            <td>49.1</td>
            <td></td>
            
        </tr>
        <tr><td>18</td>
        
            <td>48.1</td>
            <td></td>
            
            <td>55.7</td>
            <td></td>
            
        </tr>
        <tr><td>19</td>
        
            <td>89.7</td>
            <td></td>
            
            <td>81.4</td>
            <td></td>
            
        </tr>
        <tr><td>20</td>
        
            <td>0.1</td>
            <td></td>
            
            <td>0.0</td>
            <td></td>
            
        </tr>        
    </tbody>
</table>
