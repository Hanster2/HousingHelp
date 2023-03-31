# HousingHelp
print("""
Hello! Welcome to our program, we hope you find it useful. For all the questions just type the number associated with the question. for example for, "2) my problem," you would just type "2"

""")
landlord_entry = "hi"
notice_hours = "bye"
filled_form = "thanks"
arrival = "Welcome"
entry_reasons = "ex"
landlord_effort = "wrong"
three_times = "late"
excessive = "where"
lease_legality = "when"
pick_one = "why"
lease_problem_type = "what"
payment_method = "who"
pick = "how"
resigning_lease = "yeee"
sublet = "yup"
repairs = "Oh"
evictions = "Yo"
personal_evict = "lit"
renovict = "bro"
behavioural = "dude"
lack_of_payment = "yuh"
housing_expectations = "yes"
interior_structures="yeap"
internal_systems = "sleep"
exterior_structures = "apple"
appliances = "pear"
cold_hot = "Lemon"
who_pays = "JLN"
parties_fires = "happy"
noise_nuisance = "bump"
rural_urban = "ILY"
terms = "Class"
situations = "Nah"
resolve = ("""Try and resolve the problem with your landlord by bringing up this issue. In most cases landlord needs to provide 24 hours notice before they or a representative enter your home and they must come between 8am and 8pm. There are some circumstances where they do not need to give notice such as
  1) there is an emergency such as a fire or a flood
  2) The tenant allows the landlord to enter
  3) a care home tenant who has agreed to let the landlord come in to check at regular intervals
  ***If you have tried this and it does not work you can contact the 

Landlord and Tenant Board, 
Email: SO-ltb@ontario.ca

Police, 
Phone: (905) 546-4925
email: info@hamiltonpolice.ca

Crime Stoppers
Phone: 1 (800) 222-8477
Link: https://crimestoppershamilton.com

City Council, 
Phone: (905) 546-3901
Email: housing@hamilton.ca

or the Rental Housing Enforcement Unit of the Ontario Ministry of Municipal Affairs and Housing 
Phone: 1 (888) 772-9277
Email: RHEU.info@Ontario.ca""")
#Question 1
big_question = input("""Yo whats stressin u buddy? 
1) Landlord Entry
2) Leases
3) Repairs
4) Evictions
5) Standard of Living
6) Signing a Lease
""")
if big_question == "1":
#Question 2
  landlord_entry = input("""
  Did the landlord provide notice before they or a representative such as an agent, superintendent, or person hired by the landlord arrived on the property? 
  1) Yes  
  2) No
  """)
if big_question == "2":
#Question 2.1
  lease_problem_type = input("""
  I am sorry to hear that what type of lease problems are you experiencing? 

  1) Lease legality
  2) Lease payment methods
  3) Re-signing a lease
  4) Subletting 
  """)
if big_question == "3":
#Question 2.2
  repairs = input("""
  I am sorry to hear that what type of repair problems are you experiencing? 
  1) Notice of Repairs 
  2) What is the landlord’s responsibility
  3) What if the landlord does not do the repair
  """)
if big_question == "4":
  evictions = input("""
  I see, I'm sorry to hear that. What type of eviction? 
  
  1) evictions for personal use 
  2) reno-viction 
  3) behavioural related 
  4) Lack of payment
  """)
if big_question == "5":
  housing_expectations = input("""
  What is your concern? Note: always consult your tenancy agreement first. Many tenancy agreements state that any damage the tenant or their guests inflict on the home is the responsibility of the tenant to fix.

1) Interior Structures
2) Exterior Structures
3) Appliances, Smoke Alarms & Utilities or 
4) Recreation

  """)
if landlord_entry == "1":
#Question 3
  notice_hours = input("""
  Was the landlord’s notice at least 24
  hours in advance?  
  1) Yes  
  2) No 
  """)
if landlord_entry == "2":
  print(resolve)
if notice_hours == "1":
#Question 4
  filled_form = input("""
  FYI These are the methods of 
  communication your landlord can use:
  1) Phone call
  2) Text message       
  3) Email  
  4) Letter 
  5) In person  
  
  Were the following included in the
  written notice from the landlord: 
  reason for entry, date landlord     
  will enter the unit, time of entry
  (between 8am and 8pm)? 
    1) Yes  
    2) No 
    """)
if notice_hours == "2":
  print(resolve)
if filled_form == "1":
#Question 5
  arrival = input("""
  Did the landlord arrive between
  the permitted times (8am and 8pm
  ?) 
  1) Yes  
  2) No  
  """)
if filled_form == "2":
  print(resolve)
if arrival == "1":
#Question 6
  entry_reasons = input("""
  These are the reasons a
  landlord can be on your property
  1) To carry out work, a repair,
  or a replacement in the unit

  2) To allow a potential
  mortgagee or insurer of the
  residential complex to view the
  rental unit 

  3) To allow a person who holds
  a certificate of authorization
  within the meaning of the
  Professional Engineers Act or a
  certificate of practice within
  the meaning of the Architects
  Act or another qualified person
  to make a physical inspection
  of the rental unit to satisfy a
  requirement imposed under
  subsection 9  (4) of the
  Condominium Act, 1998. 
    
  4) To carry out an inspection of
  the rental unit, if, 
    a) the inspection is for the
    purpose of determining whether
    or not or not the rental unit
    is in a good state of repair
    and fit for habitation and
    complies with health, safety,
    housing and maintenance
    standards, consistent with the
    landlord's obligations under
    subsection 20(1) or section 161
    of the RTA; and 
    b) it is reasonable to carry
    out the inspection. 

    5) For any other reasonable
    reason for entry set out in the
    tenancy agreement

    Was the landlord on here for one
    of these reasons? 
  """)
if arrival == "2":
  print(resolve)
if entry_reasons == "1":
#Question 7
  landlord_effort = input("""
  Do you feel the landlord done their
  best to limit entries to the rental
  unit? 
  1) Yes  
  2) No 
  """)
if entry_reasons == "2":
  print(resolve)
#Question 8
if landlord_effort == "1":
  three_times = input("""
  Has the landlord been to the property
  more than three times since the lease
  began its duration? 
  1) Yes  
  2) No  
  """)
if landlord_effort == "2":
  print(resolve)
if three_times == "1":
  print(resolve)
if three_times == "2":
  excessive = input("""
  Do you feel your landlord is visiting excessively and for unecessary reasons?
  1) Yes
  2) No
  """)
  if excessive == "1":
    print(resolve)
  if excessive == "2":
    print("It looks like your good to go! We hope this program was able to help you. If you have any suggestions, please let us know as we are always looking to imrove! Have a great day!")
if lease_problem_type == "1":
#Question 3.1
  lease_legality = input("""Is there a specific type of lease legality issue you are having? 
  1) Yes 
  2) No
  """)
if lease_legality == "1":
#Question 4.1
  pick_one = input("""
  Which concern best fits yours?

  1) What format should the lease be? 
  2) What makes the lease valid 
  3) What to do if the landlord does not give you the lease
  """)
if lease_legality == "2":
  print("Important to note: Your landlord must be using the Ontario standard lease after 2018. This can be found on the government of Ontario website for reference of what should be included.")
if pick_one == "1":
  print("Important to note: Your landlord must be using the Ontario standard lease. This can be found on the government of Ontario website.")
if pick_one == "2":
  print("Important to note: The lease is only binding when signed by landlord and the tenant")
if pick_one == "3":
  print("Important to note: The landlord must give you a copy of the lease. If they do not provide a copy you are entitled to withhold rent after 30 days (only for a one-month time frame). At which time you should consult legal advice.")
if lease_problem_type == "2":
#Question 3.11
  pick = input(""" Which concern best fits yours?
  1) Rent deposit 
  2) Post-dated cheques 
  3) E-transfer 
  4) What to do if you cannot pay
  """)
if pick == "1":
  print("Important to note: A rent deposit is not mandatory although may be required by a landlord to secure agreement. This amount should be equal to the rent amount for one period and applied to the tenants last month’s rent. For more information please visit: https://files.ontario.ca/mmah-guide-to-standard-lease-for-rental-housing-en-2021-03-30.pdf")
if pick == "2":
  print("Important to note: Post-dated cheques are not mandatory even if a landlord says they are, as stated in the Residential Tenancy Act. The landlord and occupant have to agree on payment method. The type of rent payment cannot be specified by landlord. For further information please consult: https://tribunalsontario.ca/documents/ltb/Brochures/Guide%20to%20RTA%20(English)_dec2020.pdf")
if pick == "3":
  print("Important to note: E-transfer payment is not mandatory even if a landlord says it is. The landlord and occupant have to agree on payment method. The type of rent payment cannot be specified by landlord. For further information please consult: https://tribunalsontario.ca/documents/ltb/Brochures/Guide%20to%20RTA%20(English)_dec2020.pdf")
if pick == "4":
  print("")
if lease_problem_type == "3":
#Question 3.12
  resigning_lease = input("""
  Which concern best fits yours
  1) Re-signing terms
  2) Rent increase
  """)
if resigning_lease == "1":
  print("Important to note: The tenant can inform the landlord they plan to re-sign for the next year or fixed term. The landlord can decide whether to authorize the same lease or provide a new lease based on terms. For further information please consult: https://tribunalsontario.ca/documents/ltb/Brochures/Guide%20to%20RTA%20(English)_dec2020.pdf")
if resigning_lease == "2":
  print("Important to note: The landlord is authorized to increase the rent based on the guidelines provided in the residential tenancy act every year. The increase can be no higher for an existing resident than 2.5%. For further information and exceptions please consult: https://www.ontario.ca/page/residential-rent-increases")
if lease_problem_type == "4":
#Question 3.13
  sublet = input("""
  Are you wondering if you are able to sublet?
  1) Yes
  2)
  """)
if sublet == "yes":
  print("Important to note: Yes, tenants can sublet granted they get the approval of the landlord. Although the landlord cannot directly refuse unless they have a good reason. ")
if sublet == "No":
  print("Unfortnately this is all the infomation we currently have on subletting. If you have feedback on how we could improve we would love to hear it! Have a great day and goodluck :)")
if repairs == "1":
  print("Important to note: The tenant is responsible for notifying the landlord if the property is in need of a repair. This should be done through written notice. For further information and exceptions please consult: https://tribunalsontario.ca/documents/ltb/Brochures/Maintenance%20and%20Repairs%20(EN).html")
if repairs == "2":
  print("Important to note: The landlord is responsible for almost all property repairs unless caused by tenant or a person associated with the tenant. General up-keep is maintained by the landlord. For further information and exceptions please consult: https://tribunalsontario.ca/documents/ltb/Brochures/Maintenance%20and%20Repairs%20(EN).html") 
if repairs == "3":
  print("""Important to note: If the landlord does not perform the repair that falls under their role as landlord then the tenant can file a T6 – tenant application about maintance. For further information and exceptions please consult: 

https://tribunalsontario.ca/documents/ltb/Brochures/Maintenance%20and%20Repairs%20(EN).html 

https://tribunalsontario.ca/documents/ltb/Interpretation%20Guidelines/05%20-%20Breach%20of%20Maintenance%20Obligations.html

https://tribunalsontario.ca/documents/ltb/Tenant%20Applications%20&%20Instructions/T6_Instructions_20200401.pdf
""")
if evictions == "1":
  personal_evict = input("""
  What reason did they give?
  1) To use the unit for themselves
  2) For a family member
  3) To sell the unit
  4) No reason given
  """)
if personal_evict == "1":
  print("You do not have to move by the termination date if you want to challenge the truthfulness of the claim and/or require more time to move. The termination date set out in the notice must be 120 days from issuance and the termination date must be the last date of the rental period. If this goes through then the landlord either has to provide you with one month's rent or offer you another unit to stay at.")
if personal_evict == "2":
  print("You do not have to move by the termination date if you want to challenge the truthfulness of the claim and/or require more time to move. The termination date set out in the notice must be 120 days from issuance and the termination date must be the last date of the rental period. If this goes through then the landlord either has to provide you with one month's rent or offer you another unit to stay at.")
if personal_evict == "3":
  print("You do not have to move by the termination date if you want to challenge the truthfulness of the claim and/or require more time to move. The termination date set out in the notice must be 120 days from issuance and the termination date must be the last date of the rental period. If this goes through then the landlord either has to provide you with one month's rent or offer you another unit to stay at.")
if personal_evict == "4":
  print("""
  You may want to check exactly what the reason is. Here is some general information for when you get the asnwer. 
  You do not have to move by the termination date if you want to challenge the truthfulness of the claim and/or require more time to move. The termination date set out in the notice must be 120 days from issuance and the termination date must be the last date of the rental period. If this goes through then the landlord either has to provide you with one month's rent or offer you another unit to stay at.
  """)
if evictions == "2":
  renovict = input("""
  What reason did they give?
  1) Renovate
  2) Repair
  3) Demolish
  4) No reason given
  """)
if renovict == "1":
  print("You do not have to move by the termination date if you want to challenge the truthfulness of the claim and/or require more time to move. The termination date set out in the notice must be 120 days from issuance and the termination date must be the last date of the rental period. If the landlord is giving you this notice for extensive repairs requiring the unit to be vacant, if you do not plan to move back in once the repairs or renovations are done, the landlord must pay you an amount equal to 3 months' rent or offer you another rental unit that is acceptable to you. You may be entitled to compensation or another unit. If you plan to move back in once the repairs or renovations are done, the landlord must pay you an amount equal to 3 months' rent, or the rent for the period of time the rental unit is being repaired or renovated - whichever is less. ")
if renovict == "2":
  print("You do not have to move by the termination date if you want to challenge the truthfulness of the claim and/or require more time to move. The termination date set out in the notice must be 120 days from issuance and the termination date must be the last date of the rental period. If the landlord is giving you this notice for extensive repairs requiring the unit to be vacant, if you do not plan to move back in once the repairs or renovations are done, the landlord must pay you an amount equal to 3 months' rent or offer you another rental unit that is acceptable to you. You may be entitled to compensation or another unit. If you plan to move back in once the repairs or renovations are done, the landlord must pay you an amount equal to 3 months' rent, or the rent for the period of time the rental unit is being repaired or renovated - whichever is less. ")
if renovict == "3":
  print("You do not have to move by the termination date if you want to challenge the truthfulness of the claim and/or require more time to move. The termination date set out in the notice must be 120 days from issuance and the termination date must be the last date of the rental period. If the landlord is giving you this notice for demolition or to convert your unit to another use, the landlord must pay you an amount equal to 3 months' rent or offer you another rental unit that is acceptable to you. However, If your landlord gives you this notice because they were ordered to demolish or repair the rental unit under any law, your landlord does not have to pay you compensation for moving out.")
if evictions == "3":
  print("""
  Despite the fault being yours you still have rights. You cannot be evicted right away, your landlord needs to provide you with an N5 form informing you to correct the mentioned behaviour within 7 days. If you do not do so they can then send another N5 form wihtin 6 months that has more serious implications. EVen still you will get a hearing from teh Landlord and Tenant Board to discuss the claims being made. If this is the case contact the Hamilton Comnmunity Legal Clinic:
Phone number: (905) 527-4572
  """)
if evictions == "4":
  print("""Despite the fault being yours you still have rights. You cannot be evicted right away, your landlord needs to provide you with an N4 form. If you can pay for rent before the deadline on the N4 form you should do so in order to negate the eviction. If you cannot pay then your landlord must apply to the Landlord and Tenant Board to evict you which will lead to a hearing. If this happens contact the Hamilton Comnmunity Legal Clinic:
Phone number: (905) 527-4572 """)

if housing_expectations == "1":
#Question 3.3
  interior_structures = input("""
  Which issue relating to interior structures applies most to your concern?
  1) Water leakage
  2) locks
  3) vermin
  4) internal systems
  5) stairways
  6) repairs
  """)
if interior_structures == "1":
  print("""
  If you have water leakage, contact your landlord, these areas should be kept free from water penetration and from dampness arising from the entrance of moisture, and no mould or conditions that may cause mould should occur
  The bathroom, kitchen, laundry or shower room should have a floor covering of water-resistant material
""")
if interior_structures == "2":
  print("""
  If you have an intercom and security locking system that is not working, you can contact the landlord
  In multiple dwellings where a voice communications system between each dwelling unit and the front lobby and a security locking and release facilities for the entrance have been provided and are controlled from each dwelling unit, such facilities shall be maintained in good repair by the landlord
  """)
if interior_structures == "3":
  print("""
  Contact your landlord, a dwelling or a dwelling unit shall be kept free of infestation by pests
  Owner should keep property free of infestation by pests, which includes the presence of one rat, or mouse, and in the case of bed bugs, fleas, wasps, hornets, ants or cockroaches means the presence of more than one such insect, and in the case of wasps or hornets includes the presence of any occupied nest inside or attached to the exterior of a building
  """)
if interior_structures == "4":
#Question 4.3
  internal_systems = input("""
  Which internal system are you concerned about?

  1) Ventilation
  2) Plumbing
  3) Lighting
  """)
if internal_systems == "1":
  print("""
  If you are concerned about the air quality in your house, you can check-in with your landlord that the natural or mechanical ventilation of a room or space in your house is compliant with Building Code, as it should be regularly cleaned, and maintained
  The vent should prevent the entry of rain, snow and vermin
  """)
if internal_systems == "2":
  print("""
  Contact your landlord if the plumbing system and every plumbing fixture in a building is not properly performing its intended function, or if it has any leaks or defects
  All piping used to supply or drain water and all appurtenances thereto shall be protected from freezing
  A building to which water is available under pressure through piping shall be provided with piping for hot water at a temperature of not less than 43 degrees celsius, and cold water connected to every kitchen, bath or shower room, or laundry room, and piping for cold water connected to every toilet and hose bib
  All water supply lines shall not include any material that contain lead (unless the water supply line connects to a portion of the City water system that itself is constructed of materials that contain lead)
  """)
if internal_systems == "3":
  print("""
  Contact your landlord if there is insufficient lighting, there should be a permanently installed working light maintained and properly functioning in all stairways, exterior exits, entrance doorways, bath or shower rooms, toilet rooms, kitchens, corridors, basement, laundry room and utility room
  There should be sufficient illumination to provide a safe passage in hallways, stairways, common areas and underground parking areas
  """)
if interior_structures == "5":
  print("If your interior stairway has more than 2 risers it shall have at least one handrail sufficient to prevent an accidental fall and such handrail shall be repaired or replaced if damaged")
if interior_structures == "6":
  print("Any repair or replacement to a wall or ceiling shall have a similar finish to that of the original covering and comparable to surrounding finishes")
if housing_expectations == "2":
#Question 3.31
  exterior_structures = input("""
  Which exterior structure issue fits your concern
  1) Water Leakage
  2) Entries & Exits
  3) Deterioration
  4) Renovations
  5) Stairways
  """)
if exterior_structures == "1":
  print("The landlord should assure that all exterior walls and the roof should be maintained to prevent leakage of water and exterior walls should be waterproofed")
if exterior_structures == "2":
  print("""
  -The principal entrance of a building shall be accessed by a walkway leading to a road or another hard-surfaced area, which should have surfaced maintained to afford safe passage (either by the landlord or tenant, depending on the contract)
  -If your contract states that the tenant is responsible for snow removal, within 24 hours of the cessation of a winter storm, remove and clear all snow and ice from the property
  -Do not obstruct access to a fire hydrant
  -Do not obstruct drainage to any drain or sewer
  -Do not interfere with the safe passage of vehicles or pedestrians
  -If your contract states the landlord is responsible for snow removal, within 24 hours of the cessation of a winter storm, they must do so
  -Ensure any vehicles parked in the driveway are driven to another spot to get the driveway free of snow
  -The landlord should ensure locks are properly functioning or repair or replace them if damaged
  -Doors and windows should be capable of being locked from the outside and either locked/secured from the inside
  -The landlord should repair any broken windows
  -The landlord should prevent the entry of vermin and birds by securing all exterior surfaces of the building
  -If any doors, windows, hatches, or other openings in your house are damaged, the landlord should repair or replace them to minimize drafts and heat loss
  -Includes rotted or missing weather-stripping, caulking or hardware
  -Includes broken or missing glass
  -Includes ensuring that windows that are designed to be opened are fitted with screens to prevent the entrance of insects and rodents
  -If you have a child younger than 10 years old, you can send a written request to the owner to provide and install a protective device on any window that has: a moveable sash & is more than 1.8 meters above the adjacent finished ground level
  -The protective device shall be installed within 7 days of delivery of the written request, and should prevent the opening of a window to any amount greater than 100 mm
  """)
if exterior_structures == "3":
  print("""
  -The landlord should ensure that the exterior surfaces are free from loose, insufficiently secured, rotten, warped or broken materials, and such objects shall be removed, repaired or replaced
  -If you are concerned about an unhealthy tree on the property, contact your landlord, as a tree that is dead, or part of a tree that is dead, or in a decayed or damaged condition, and that may be hazardous to persons or property, shall be removed
  -Be careful to not remove trees on city property, this is the responsibility of the city
  """)
if exterior_structures == "4":
  print("When opened or replaced during the course of alterations or renovations, the landlord should ensure the building is insulated to minimize heat loss, air infiltration and moisture condensation on the interior surfaces")
if exterior_structures == "5":
  print("""
  -If your exterior stairway has more than 3 risers and less than 7 risers, it should have at least one handrail sufficient to prevent an accidental fall and such handrail shall be repaired or replaced if damaged
    -A partial or short wall on either side could be sufficient
  -If your exterior stairway has more than 6 risers, with a difference in elevation at any point from the adjacent finished ground or floor of more than 600 mm shall be protected by Building Code compliant guards on all open sides sufficient to prevent an accidental fall
  """)
if housing_expectations == "3":
  appliances = input("""
  Which one exactly?
  1) Appliances
  2) Smoke Alarms
  3) Utilities
  """)
if appliances == "1":
  cold_hot = input("""Which topic regarding appliances best fits your need?
  1) Seeking hot air
  2) Seeking cold air
  3) Maintenance
  """)
if cold_hot == "1":
  print("""
  The furnace in your house should supply
  heat of at least 20 degrees celsius in
  all spaces where people live from
  September 15 to May 15 of each year. 
  
  These spaces include where people live,
  eat, sleep or cook, and does not
  include spaces such as laundry rooms,
  storage spaces, communicating
  corridors, stairways, boiler rooms,
  mechanical rooms, garages designed for
  parking, or elevator shafts.
  
  Cannot be heated by a temporary heating
  device, which is any electric heating
  device which plugs into or is intended
  to plug into an electrical outlet, or
  any heating device which is designed to
  be portable
  """)
if cold_hot == "2":
  print("""
  If there is a functioning air conditioner that your landlord agreed would be functioning (note if a functioning air conditioner is included in tenancy contract) in your house, it should be maintained in a state of good repair and be operable, with the responsibility on the landlord to maintain it (given you did not damage it yourself)
  """)
if cold_hot == "3":
  print("""
  Contact your landlord, as appliances including (but are not limited to), a stove, refrigerator, clothes washer, clothes dryer, dishwasher, air conditioner or a hot water tank, these should be maintained in a good state of repair and in a safe operable condition
  """)
if appliances == "2":
  print("Smoke alarms should be installed on ALL floor levels and outside of sleeping areas in homes. It is the landlord’s responsibility to install and maintain smoke alarms, and it is your responsibility to inform the landlord about any problems or concerns regarding smoke alarms")
if appliances == "3":
  who_pays = input("""
  Who is responsible for obtaining and maintaining utilities?
  1) Tenant
  2) Landlord
  """)
if who_pays == "1":
  print("make sure that you have paid your bills in a timely manner, because if nonpayment is a reason for why your utilities are not functioning properly, the responsibility is on you to fix the issue")
if who_pays == "2":
  print("reach out to your landlord if the utilities are not functioning properly. The landlord should notify the tenants if a vital service will be shut off for any period of time, the notice should be given at least 24 hours in advance given what is practicable under the circumstances. The landlord can cease to provide a vital service only to alter or repair the rental unit and only for the minimum period of time necessary to affect the alteration or repair.")
if housing_expectations == "4":
  parties_fires = input("""
  What is your recreation related concern?
  1) Hosting Parties
  2) Outdoor fires
  """)
if parties_fires == "1":
  noise_nuisance = input("""
  What about hosting parties?
  1) Noise
  2) Public Nuisance
  """)
if noise_nuisance == "1":
  print("""
  Reasonable noise - If you are hosting a party likely to make reasonable noise that will not disturb inhabitants of the city, you do not need a permit
  Unreasonable noise - If you are hosting a party likely to make unreasonable noise that will likely disturb the inhabitants of the city, you need to apply for an exemption permit from the City of Hamilton under the category of “noise from a short term event on private property”
https://live-city-of-hamilton.pantheonsite.io/city-council/by-laws-enforcement/search-by-laws?keywords=Noise%20Control&category=All&sort_bef_combine=number_DESC
  """)
if noise_nuisance == "2":
  print("""
  Boundaries to set at social gatherings:
  -No public drunkenness
  -No public brawls/fights
  -No unlawful distribution of alcohol or
  controlled substances
  -No damage to public or private property
  -No unlawful fireworks or open-burning
  fires
  -No entering the house through the roof
  (unless it is a legitimate entry point)
  -No blocking pedestrian/vehicular traffic
  -No depositing trash on private/public
  property
  """)
if parties_fires == "2":
  rural_urban = input(""" 
  Do you live in an urban or rural area?
  1) Urban
  2) Rural
  """)
if rural_urban == "1":
  print("- you can have an outdoor propane or natural gas fire pit or a small confined fire that is supervised at all times and used to cook food on a grill of BBQ. If you want a fire outside of the aforementioned conditions, you can apply for an open air burning permit with written authorization from the property owner. The fire department will inspect your property before issuing a permit to make sure it will not be nuisance or risk to others.")
if rural_urban == "2":
  print("you can have an outdoor propane or natural gas fire pit or a small confined fire that is supervised at all times and used to cook food on a grill of BBQ. If you want a fire outside of the aforementioned conditions, you can apply for an open air burning permit with written authorization from the property owner.")
if big_question == "6":
  terms = input("""
  What part of the searching process are you concerned with?
  1) What  can you be asked to provide by a landlord
  2) What cannot be asked of you in an interview/you have no obligation to answer
  3) What you cannot be asked in a rental application (doing so woul dbe illegal)
  4) What a landlord cannot make you pay for in the lease
  5) Miscellaneous situations that you may have experienced in your search
  """)
if terms == "1":
  print("""
  Your landlord can and may ask you for these:

  1) Credit check  
  2) Guarantor  
  3) References  
  1) Number of people you’ll be living with 
  2) Proof of income  
  """)
if terms == "2":
  print("""
  hese things CANNOT be asked of you in an interview:

  1) Age 
  2) Race 
  3) Citizenship 
  4) Ethnic origin/religion 
  5) Disability 
  6) Marital status  
  7) Family status 
  8) Gender identity 
  9) Sex 
  10) Sexual orientation  
  11) If you’re on welfare of public assistance 
  12) If you smoke 
  """)
if terms == "3":
  print("""
  These things CANNOT be asked of you in a rental application:

  1) Age  
  2) Gender or sexual orientation 
  3) Medical history 
  4) Credit card numbers 
  """)
if terms == "4":
  print("""
  Your landlord cannot ask you to cover these costs in your lease:

  1) Real estate agent fees  
  2) Property taxes  
  3) Home maintenance costs  
  4) Utilities such as water if included in rent  
  """)
if terms == "5":
  situations = input("""
  which of these situations best describes yours?
  1) The monthly rent is much less than the current market rate 
  1) You’re asked to leave a deposit without any formal rental agreement or lease in place 
  3) You’re asked to send a security deposit to a landlord outside the country 
  4) You’re offered a rental unit without a background check 
  5) When you ask about the rental unit, you get an email that sends you to a website asking for personal or financial information 
  6) Ads show pictures of the outside of the unit only, or pictures that don’t match the actual property 
""")
if situations == "1":
  print("")
