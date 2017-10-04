// ETML
// Auteur : Monteroni
// Date : 04.10.2017
// Description : Test formatif
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp1
{
    class Memo
    {
        public string strMessage;                               // recupera le memo 
        DateTime writeDate =new DateTime();                     // Recupera la date où on écrit le memo
        /// <summary>
        /// Constructeur
        /// </summary>
        /// <param name="pMemo">Memo de l'utilisateur</param>
        public Memo (string pMemo)
        {
            strMessage = pMemo;
            writeDate = DateTime.Now;
        }
        /// <summary>
        /// Ecrit la date du moment où à été écris le memo
        /// </summary>
        /// <returns> Recuper la date du memo</returns>
        public DateTime GetMemoDate()
        {
            return writeDate;
        }
    }
}
