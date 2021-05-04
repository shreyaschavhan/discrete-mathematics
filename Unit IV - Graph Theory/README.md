# Unit IV - Graph Theory

## &#10023; Syllabus:

> * Graph Terminology and Special types of Graphs
> * Representing Graphs and Graph Isomorphism
> * Connectivity
> * Euler and Hamilton Paths
> * The handshaking lemma
> * Single source shortest path -
>   * Dijkstra's Algorithm
> * Planar Graphs
> * Graph Colouring

---

## &#10023; Graph Theory:



> * ![image](https://user-images.githubusercontent.com/68887544/116778438-84cced80-aa8f-11eb-8bab-cd835ad663a6.png)
> * ![image](https://user-images.githubusercontent.com/68887544/116778458-a5954300-aa8f-11eb-8a26-4126b8c5c48e.png)
> * ![image](https://user-images.githubusercontent.com/68887544/116778473-bc3b9a00-aa8f-11eb-8c0b-78acbae6ce88.png)
> * ![image](https://user-images.githubusercontent.com/68887544/116778477-c2ca1180-aa8f-11eb-9aca-629fe54c3fac.png)
> * ![image](https://user-images.githubusercontent.com/68887544/116778488-cfe70080-aa8f-11eb-8a84-455c1e61825f.png)
> * ![image](https://user-images.githubusercontent.com/68887544/116778497-da08ff00-aa8f-11eb-8323-244d95625e87.png)
> * ![image](https://user-images.githubusercontent.com/68887544/116778502-e3926700-aa8f-11eb-8a18-959ac1af3ebb.png)
> * ![image](https://user-images.githubusercontent.com/68887544/116778508-e7be8480-aa8f-11eb-9c3d-2531e93097c3.png)
> 

----

* Examples:
> * ![image](https://user-images.githubusercontent.com/68887544/116779191-6c120700-aa92-11eb-94c3-acfb2a10609b.png)
> ---
> * ![image](https://user-images.githubusercontent.com/68887544/116779202-84822180-aa92-11eb-94f7-a69c456d1f4a.png)
> ---
> * ![image](https://user-images.githubusercontent.com/68887544/116779223-a5e30d80-aa92-11eb-8650-4cff26478a42.png)
> ---
> * ![image](https://user-images.githubusercontent.com/68887544/116779241-beebbe80-aa92-11eb-8898-1eac3c5e362e.png)
> ---
> * ![image](https://user-images.githubusercontent.com/68887544/116779337-649f2d80-aa93-11eb-8a32-82127a2386df.png)
> ---
> * ![image](https://user-images.githubusercontent.com/68887544/116779347-800a3880-aa93-11eb-99d5-48b2b0c31e29.png)
> ---
> * ![image](https://user-images.githubusercontent.com/68887544/116779365-a0d28e00-aa93-11eb-863c-98f89bdca56d.png)

---

> * ![image](https://user-images.githubusercontent.com/68887544/116779938-d3ca5100-aa96-11eb-9b18-3db43a0f9737.png)
> ---
>  * ![image](https://user-images.githubusercontent.com/68887544/116779952-e80e4e00-aa96-11eb-8ae4-05a3bb1f1cb9.png)
>  ---
> * ![image](https://user-images.githubusercontent.com/68887544/116779965-fa888780-aa96-11eb-92e3-5ca5af257056.png)

---

> * ![image](https://user-images.githubusercontent.com/68887544/116781228-463f2f00-aa9f-11eb-91ef-698aaf7bfa7e.png)
> ---
> * ![image](https://user-images.githubusercontent.com/68887544/116781292-94543280-aa9f-11eb-8e85-79f9aa0a56bb.png)
> * ![image](https://user-images.githubusercontent.com/68887544/116781298-a2a24e80-aa9f-11eb-82fd-fac08fc5993c.png)
> ---
> * ![image](https://user-images.githubusercontent.com/68887544/116781325-ccf40c00-aa9f-11eb-9c92-1b908e03e410.png)
> * ![image](https://user-images.githubusercontent.com/68887544/116781338-d7160a80-aa9f-11eb-942a-a536d4fafcca.png)
> ---
> * ![image](https://user-images.githubusercontent.com/68887544/116781367-062c7c00-aaa0-11eb-90f6-70789dcb730f.png)
> ---
> * ![image](https://user-images.githubusercontent.com/68887544/116781375-147a9800-aaa0-11eb-86fd-196d6b91cd3a.png)
> ---
> * ![image](https://user-images.githubusercontent.com/68887544/116781383-24927780-aaa0-11eb-9850-dcb8436d35a5.png)
> ---
> * ![image](https://user-images.githubusercontent.com/68887544/116781402-3e33bf00-aaa0-11eb-91c4-e179226e5334.png)

---

* Hamiltonian Path:
> * ![image](https://user-images.githubusercontent.com/68887544/116804900-42afb480-ab40-11eb-9794-4e6e1e5258c5.png)
> ---
> * ![image](https://user-images.githubusercontent.com/68887544/116804932-6ffc6280-ab40-11eb-8f48-ece8bea8a292.png)
> ---
> * ![image](https://user-images.githubusercontent.com/68887544/116805003-f153f500-ab40-11eb-8443-b7b53eb85765.png)
> ---
> * ![image](https://user-images.githubusercontent.com/68887544/116805037-27917480-ab41-11eb-9021-4b3180758d32.png)
> * ![image](https://user-images.githubusercontent.com/68887544/116805046-3aa44480-ab41-11eb-87a8-3a8bc1bbdefc.png)
> ---
> * ![image](https://user-images.githubusercontent.com/68887544/116805093-8525c100-ab41-11eb-93e1-b0bffa4b8078.png)
> * ![image](https://user-images.githubusercontent.com/68887544/116805094-92db4680-ab41-11eb-9781-4ce272a5b8f5.png)
> ---
> * Nearest neighbour method:
>   * ![image](https://user-images.githubusercontent.com/68887544/116805162-1f860480-ab42-11eb-9389-c21d6b9544c6.png)
>   * ![image](https://user-images.githubusercontent.com/68887544/116805170-2d3b8a00-ab42-11eb-9b59-edf620c7ce2e.png)
>   * ![image](https://user-images.githubusercontent.com/68887544/116805193-522ffd00-ab42-11eb-8014-dc6aa14856ee.png)
>   * ---
>   * ![image](https://user-images.githubusercontent.com/68887544/116805236-a509b480-ab42-11eb-846c-2ee316d2445a.png)
>   * ![image](https://user-images.githubusercontent.com/68887544/116805258-bbb00b80-ab42-11eb-9a1a-4dbb242bd323.png)
>   * ![image](https://user-images.githubusercontent.com/68887544/116805267-c9fe2780-ab42-11eb-94a4-b6199865d360.png)
>   * ![image](https://user-images.githubusercontent.com/68887544/116805275-d84c4380-ab42-11eb-8fc0-dc0bf25dc877.png)
>   
---

* Dijkstros Algorithm:
> * Steps:
>   * ![image](https://user-images.githubusercontent.com/68887544/116805457-607f1880-ab44-11eb-81ec-4b8e1791b851.png)
>   * ![image](https://user-images.githubusercontent.com/68887544/116805461-6e349e00-ab44-11eb-8eef-cc5f14b14277.png)
>   * ![image](https://user-images.githubusercontent.com/68887544/116805470-7bea2380-ab44-11eb-905a-37d684f4c062.png)
>   * ![image](https://user-images.githubusercontent.com/68887544/116805482-8a383f80-ab44-11eb-9dae-53b3740d53c0.png)
> ---
> * Examples:
>   * ![image](https://user-images.githubusercontent.com/68887544/116805509-a3d98700-ab44-11eb-862e-70dfea483c92.png)
>   * ![image](https://user-images.githubusercontent.com/68887544/116805522-b227a300-ab44-11eb-84e5-21c5f6868dba.png)
>   * ![image](https://user-images.githubusercontent.com/68887544/116805528-bf449200-ab44-11eb-99d7-f876837c8a3f.png)
>   * ![image](https://user-images.githubusercontent.com/68887544/116805536-cbc8ea80-ab44-11eb-8d00-7d2fc421e3c8.png)
>   * ![image](https://user-images.githubusercontent.com/68887544/116805545-d8e5d980-ab44-11eb-8a79-30a4ee5d260e.png)
>   * ![image](https://user-images.githubusercontent.com/68887544/116805550-e307d800-ab44-11eb-8ecc-e050be31bbf4.png)
>   * ![image](https://user-images.githubusercontent.com/68887544/116805559-eef39a00-ab44-11eb-9068-3bc094b9a84b.png)
>   * ![image](https://user-images.githubusercontent.com/68887544/116805570-fca91f80-ab44-11eb-909f-014b7d16e4c1.png)
>   * ![image](https://user-images.githubusercontent.com/68887544/116805584-13e80d00-ab45-11eb-8a1e-30dda367ec95.png)
>   * ---
>   * ![image](https://user-images.githubusercontent.com/68887544/116805602-324e0880-ab45-11eb-84d5-d90f0059abdf.png)
>   * ![image](https://user-images.githubusercontent.com/68887544/116805610-3d089d80-ab45-11eb-80d2-87e75b7d0172.png)
>   * ![image](https://user-images.githubusercontent.com/68887544/116805613-472a9c00-ab45-11eb-91b8-482651e79a96.png)
>   * ![image](https://user-images.githubusercontent.com/68887544/116805622-527dc780-ab45-11eb-910c-5a3a0c1c581c.png)
>   * ![image](https://user-images.githubusercontent.com/68887544/116805630-61fd1080-ab45-11eb-9c34-6de162b90cd2.png)
>   * ![image](https://user-images.githubusercontent.com/68887544/116805658-7ccf8500-ab45-11eb-9ba0-bbe808d5885f.png)
>   * ![image](https://user-images.githubusercontent.com/68887544/116805671-91ac1880-ab45-11eb-8a5a-4d9b07cc41e9.png)
>   * ![image](https://user-images.githubusercontent.com/68887544/116805690-abe5f680-ab45-11eb-92e4-77f8e9a6f16c.png)
>   * ![image](https://user-images.githubusercontent.com/68887544/116805698-b7d1b880-ab45-11eb-8dd3-22d42732e834.png)
>   

--- 
> P.S. Done Unit IV - Graph Theory
























