# EX01 Developing a Simple Webserver
## Date:

## AIM:
To develop a simple webserver to serve html pages.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Serving the HTML pages.

### Step 5:
Testing the webserver.

## PROGRAM:
<!DOCTYPE html>
<html>
    
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <script src="https://cdn.tailwindcss.com"></script>
    </head>
    
    <body>
        <div class="max-w-[90rem] mx-auto">
            <div class="shadow-[0px_4px_4px_0px_rgba(0,0,0,0.3)]">
                <img class="block" src="./assets/image-53025.076097736965.png" />
                <p class="block text-center text-[0.94rem] text-white ">Made with love by me, Myself and I</p>
                <img class="block" src="./assets/image-82080.51454183005.png"
                />
            </div>
            <div>
                <div>
                    <img class="block" src="./assets/image-27743.173511979345.png" />
                    <div class="shadow-[-2px_-2px_8px_0px_rgba(255,255,255,0.5)]">
                        <img class="block" src="./assets/image-62786.25976380992.png" />
                        <img class="block" src="./assets/image-45592.171840215626.png" />
                    </div>
                    <div class="shadow-[-2px_-2px_8px_0px_rgba(255,255,255,0.5)]">
                        <img class="block" src="./assets/image-57955.53030057321.png" />
                        <img class="block" src="./assets/image-67124.07224057087.png" />
                    </div>
                    <div>
                        <p class="block text-center text-[0.94rem] text-white ">First Name :</p>
                        <img class="block" src="./assets/image-28197.580186745385.png"
                        />
                    </div>
                    <div>
                        <p class="block text-center text-[0.94rem] text-white ">Email id :</p>
                        <img class="block" src="./assets/image-88411.98690572694.png"
                        />
                    </div>
                    <div>
                        <p class="block text-center text-[0.94rem] text-white ">MEssage :</p>
                        <img class="block" src="./assets/image-78725.5810551778.png"
                        />
                        <img class="block" src="./assets/image-43439.892163024444.png" />
                        <img class="block" src="./assets/image-35804.378850627174.png" />
                    </div>
                    <div>
                        <p class="block text-center text-[0.94rem] text-white ">LAst Name :</p>
                        <img class="block" src="./assets/image-42741.231339274746.png"
                        />
                    </div>
                    <div>
                        <div>
                            <img class="block" src="./assets/image-62730.1882175552.png" />
                            <img class="block" src="./assets/image-69472.59288969554.png" />
                            <img class="block" src="./assets/image-87923.87174227423.png" />
                        </div>
                        <div>
                            <img class="block" src="./assets/image-23167.82975161371.png" />
                            <img class="block" src="./assets/image-53205.410504292195.png" />
                            <img class="block" src="./assets/image-49829.83828155372.png" />
                        </div>
                        <div>
                            <img class="block" src="./assets/image-25833.555568344193.png" />
                        </div>
                        <div>
                            <img class="block" src="./assets/image-78876.91205231122.png" />
                            <img class="block" src="./assets/image-55914.83139044111.png" />
                        </div>
                    </div>
                    <div class="flex flex-row gap-2.5 justify-center items-center overflow-hidden px-[2.19rem] py-[0.44rem] border-white border rounded-[1.88rem]">
                        <p class="block text-center text-[0.94rem] text-white ">Submit</p>
                    </div>
                </div>
            </div>
            <div>
                <div>
                    <img class="block" src="./assets/image-4977.253566421913.png" />
                    <img class="block" src="./assets/image-53466.51129769757.png" />
                    <img class="block" src="./assets/image-35862.53969345503.png" />
                </div>
                <div>
                    <img class="block" src="./assets/image-95584.41823525248.png" />
                    <div>
                        <img class="block" src="./assets/image-8163.627777435778.png" />
                        <div>
                            <div>
                                <img class="block" src="./assets/image-92988.08641487214.png" />
                                <img class="block" src="./assets/image-50934.63028575287.png" />
                                <img class="block" src="./assets/image-59114.92087135673.png" />
                            </div>
                        </div>
                        <div>
                            <img class="block" src="./assets/image-73706.86128297515.png" />
                            <img class="block" src="./assets/image-4282.416453424687.png" />
                        </div>
                        <img class="block" src="./assets/image-20813.53082576327.png" />
                        <p class="block text-right text-xl text-white ">Click!</p>
                    </div>
                    <img class="block" src="./assets/image-1557.472174038499.png" />
                    <img class="block" src="./assets/image-4923.036423616844.png" />
                    <img class="block" src="./assets/image-84423.57589833169.png" />
                    <img class="block" src="./assets/image-70110.51662234662.png" />
                </div>
            </div>
            <div>
                <div>
                    <img class="block" src="./assets/image-37305.75092576101.png" />
                    <img class="block" src="./assets/image-85741.33177827763.png" />
                    <img class="block" src="./assets/image-26778.575798763726.png" />
                </div>
                <div>
                    <div>
                        <img class="block" src="./assets/image-38170.778670836095.png" />
                        <p class="block text-right text-[1.67rem] text-white ">DSA</p>
                    </div>
                    <div>
                        <img class="block" src="./assets/image-98869.67950172567.png" />
                        <p class="block text-right text-[1.67rem] text-white ">DBMS</p>
                    </div>
                    <div>
                        <img class="block" src="./assets/image-82577.25610332664.png" />
                        <p class="block text-right text-[1.67rem] text-white ">OS</p>
                    </div>
                    <div>
                        <img class="block" src="./assets/image-983.9555703596182.png" />
                        <p class="block text-right text-[1.67rem] text-white ">FIgma</p>
                    </div>
                    <div>
                        <img class="block" src="./assets/image-88310.11298817537.png" />
                        <p class="block text-right text-[1.67rem] text-white ">SQL</p>
                    </div>
                    <div>
                        <img class="block" src="./assets/image-75346.19720911453.png" />
                        <p class="block text-right text-[0.98rem] text-white ">HTML</p>
                    </div>
                    <div>
                        <img class="block" src="./assets/image-46995.834761612685.png" />
                        <p class="block text-right text-[0.98rem] text-white ">SDLC</p>
                    </div>
                    <div>
                        <img class="block" src="./assets/image-68222.51184125929.png" />
                        <p class="block text-right text-[0.84rem] text-white ">CLOUD</p>
                    </div>
                    <div>
                        <img class="block" src="./assets/image-73366.19408894272.png" />
                        <p class="block text-right text-[0.98rem] text-white ">postman</p>
                    </div>
                    <div>
                        <img class="block" src="./assets/image-80283.93801976237.png" />
                        <p class="block text-right text-[0.98rem] text-white ">OOPS</p>
                    </div>
                    <div>
                        <img class="block" src="./assets/image-32834.13808561604.png" />
                        <p class="block text-right text-[0.98rem] text-white ">GIT</p>
                    </div>
                    <div>
                        <img class="block" src="./assets/image-62162.19694654026.png" />
                        <p class="block text-right text-[0.98rem] text-white ">C++</p>
                    </div>
                    <div>
                        <img class="block" src="./assets/image-31297.42868254708.png" />
                        <p class="block text-right text-[0.98rem] text-white ">JS</p>
                    </div>
                    <div>
                        <img class="block" src="./assets/image-5976.101776755049.png" />
                        <p class="block text-right text-[0.98rem] text-white ">CSS</p>
                    </div>
                    <div>
                        <img class="block" src="./assets/image-28126.324309342854.png" />
                        <p class="block text-right text-[2.79rem] text-white ">Skills</p>
                        <p class="block text-right text-[1.40rem] text-white ">My Tech</p>
                    </div>
                </div>
                <div>
                    <div class="blur-[2.700000047683716px]">
                        <img class="block" src="./assets/image-91297.28893532648.png" />
                    </div>
                    <p class="block text-right text-[NaNrem] text-white ">ME!!</p>
                    <div>
                        <div>
                            <img class="block" src="./assets/image-50612.83261342866.png" />
                            <img class="block" src="./assets/image-60202.13301364008.png" />
                        </div>
                    </div>
                </div>
                <div>
                    <div>
                        <div>
                            <img class="block" src="./assets/image-3030.4206676593058.png" />
                            <img class="block" src="./assets/image-47924.79162345485.png" />
                        </div>
                    </div>
                    <p class="block text-right text-xl text-white ">My hobby</p>
                    <p class="block text-right text-[1.56rem] text-white ">Designing</p>
                </div>
                <div>
                    <p class="block text-center text-[NaNrem] text-white ">Bachelor of Technology IT. Saveetha engineering college 2024- current
                        Higher Secondary Certification GHS school,vadacheri,ambur 2021-2022</p>
                    <div>
                        <div>
                            <img class="block" src="./assets/image-53143.98954537203.png" />
                            <img class="block" src="./assets/image-59692.37584723395.png" />
                        </div>
                    </div>
                    <p class="block text-right text-xl text-white ">My qualifications</p>
                </div>
            </div>
            <div>
                <div>
                    <div>
                        <img class="block" src="./assets/image-90585.11215959908.png" />
                        <img class="block" src="./assets/image-79977.1511737688.png" />
                        <img class="block" src="./assets/image-92380.40887143629.png" />
                    </div>
                    <div>
                        <div>
                            <img class="block" src="./assets/image-19878.886998269096.png" />
                            <img class="block" src="./assets/image-13362.371766011294.png" />
                            <img class="block" src="./assets/image-11006.24860191337.png" />
                        </div>
                        <div>
                            <img class="block" src="./assets/image-11782.683441173458.png" />
                            <img class="block" src="./assets/image-21320.53620012555.png" />
                            <img class="block" src="./assets/image-58453.079923967976.png" />
                        </div>
                        <div>
                            <img class="block" src="./assets/image-64740.70579484321.png" />
                        </div>
                        <div>
                            <img class="block" src="./assets/image-97705.36172427509.png" />
                            <img class="block" src="./assets/image-60564.24102700495.png" />
                        </div>
                    </div>
                    <div>
                        <img class="block" src="./assets/image-47545.815660281645.png" />
                        <p class="block text-right text-xl text-white ">Resume</p>
                        <div>
                            <img class="block" src="./assets/image-14865.479091995892.png" />
                            <img class="block" src="./assets/image-89950.92781252587.png" />
                            <img class="block" src="./assets/image-70425.96880387182.png" />
                        </div>
                    </div>
                    <div>
                        <p class="block text-right text-[6.25rem] ">I am CHANDRU</p>
                        <p class="block text-right text-xl text-white ">hi me as a seasoned UI designer specializing in creating elegant and intuitive
                            digital interfaces. With basic of experience, excel in transforming complex
                            concepts into visually stunning designs. Proficient in industry-standard
                            tools like Adobe XD and Figma, are passionate about delivering high-quality
                            solutions that enhance user experiences. ---.</p>
                    </div>
                    <div>
                        <div>
                            <div>
                                <img class="block" src="./assets/image-33490.920424961754.png" />
                                <img class="block" src="./assets/image-34274.72963393923.png" />
                                <img class="block" src="./assets/image-67567.33278638845.png" />
                            </div>
                            <img class="block" src="./assets/image-95043.43308680323.png" />
                            <img class="block" src="./assets/image-72658.90714312873.png" />
                            <img class="block" src="./assets/image-1657.8114330100257.png" />
                            <img class="block" src="./assets/image-30401.384268098507.png" />
                            <img class="block" src="./assets/image-22941.392070667254.png" />
                        </div>
                        <img class="block" src="./assets/image-77783.30670138149.png" />
                        <img class="block" src="./assets/image-31916.93630936081.png" />
                    </div>
                    <div class="opacity-[0.30]">
                        <img class="block" src="./assets/image-29877.076806123747.png" />
                    </div>
                </div>
                <div>
                    <p class="block text-[0.94rem] text-white ">L</p>
                    <p class="block text-[0.94rem] text-white ">i</p>
                    <p class="block text-[0.94rem] text-white ">g</p>
                    <p class="block text-[0.94rem] text-white ">h</p>
                    <p class="block text-[0.94rem] text-white ">t</p>
                    <p class="block text-[0.94rem] text-white "> </p>
                    <p class="block text-[0.94rem] text-white ">M</p>
                    <p class="block text-[0.94rem] text-white ">o</p>
                    <p class="block text-[0.94rem] text-white ">d</p>
                    <p class="block text-[0.94rem] text-white ">e</p>
                </div>
            </div>
            <div class="bg-black shadow-[0px_-8px_26.2px_0px_rgba(179,54,255,1)]">
                <p class="block text-center text-3xl text-purple-500 ">WELCOME !</p>
                <div class="flex flex-row gap-[4.56rem] justify-center items-center">
                    <div>
                        <p class="block text-center text-3xl text-white ">HOME</p>
                    </div>
                    <div>
                        <p class="block text-center text-3xl text-white ">About</p>
                    </div>
                    <div>
                        <p class="block text-center text-3xl text-white ">Projects</p>
                    </div>
                    <div>
                        <p class="block text-center text-3xl text-white ">Contact me</p>
                    </div>
                </div>
            </div>
        </div>
    </body>

</html>

## OUTPUT:
Dark.png

## RESULT:
The program for implementing simple webserver is executed successfully.
