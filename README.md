# Benzy
Office tasks
namespace DTO.Entity
{
    public class ClsFLTIntTrvItiReq
    {
     public string WPSourceRegion { get; set; }// needed to add this property 1st case
    }
    }
}
namespace DTO.Entity
{
    public class ClsFLTIntTrvItiReq
    {

    public string WPSourceRegion { get; set; }//// needed to add this property 2nd  case
    }
}
-------------------------
    second case 
    GetTravelItineraryWebConnectInternational
    this function                  ObjItineraryTransactionRequestInt = GenerateTravelItineraryInternationalRequest(LCC.WPConnect, LCC.WPConnect);

    we have to add 
